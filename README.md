# StockPredict
Dự án mã nguồn mở dự đoán và đánh giá chứng khoán, cổ phiếu, trái phiếu doanh nghiệp sử dụng machine learning hỗ trợ ra quyết định đầu tư, chốt lời, chốt lỗ, lên kế hoạch đầu tư, định giá .

- Ý tưởng: Bối cảnh thị trường chứng khoán hiện nay chủ yếu dựa trên tâm lý đám đông và và xu thế chung của thị trường cũng như sự ảnh hưởng của các vấn đề kinh tế chính trị trong nước và các quốc gia có tầm ảnh hưởng. Biết rằng thị trường chứng khoán thường biến động và không có quy luật, nhưng mọi thứ đều đi theo quy luật chung của giao dịch và tiền tệ cũng như phụ thuộc vào sự điều chỉnh của nhà nước. Hệ thống sẽ hộ trợ một phần nào hỗ trợ cho việc đầu tư hiệu quả và tối ưu hơn bằng việc sử dụng bigdata, khai phá dữ liệu, machine learning, **hỗ trợ thôi nhé**

- Chứng khoán cùng với ngân hàng, bảo hiểm là 3 trụ cột tài chính, kinh tế lớn của 1 quốc gia một quốc gia giàu mạnh hay không người ta nhìn vào các vấn đề an sinh xã hội thị trường chứng khoán cũng như tỷ lệ lạm phát. Vì vậy việc đầu tư chứng khoán là việc giúp các doanh nghiệp trong nước có vốn để làm ăn tạo giá trị cho xã hội, nhưng để đồng tiền đến đúng người,đúng  công ty thì cần có kinh nghiệm, những phân tích về ngành nghề và lĩnh vực kinh doanh cũng như cái nhìn về thị trường, nắm bắt được điều này nên mình bắt tay vào nghiên cứu một dự án để phục vụ cá nhân mình cho việc đầu tư, và mình muốn open source

## Yêu cầu về kiến thức 
- Đống  kiến thức bên dưới bạn không cần phải biết hết nhưng mà biết hết thì càng tốt, bạn sẽ chọn 1 module rồi code chuyên sâu về cái đó để thành thạo công nghệ đó rồi nếu bạn thích thì có thể nhẩy qua module khác để luyện công nghệ khác, code của bạn sẽ được mọi người review trước khi được merge vào master, để đóng góp cho dự án và trở thành contrib bạn hãy commit và tạo pull request 
### Điều kiện tiên quyết để tham gia dự án 
Bạn sẽ không thể tham gia dự án nếu bạn không biết sử dụng **GITHUB** để làm việc nhóm

### Đối với backend 
1. sử dụng thành thạo ubuntu hoặc MacOs quan trọng là [terminal](https://www.howtogeek.com/412055/37-important-linux-commands-you-should-know/)
2. Biết sử dụng docker [Docker document](https://docs.docker.com/)
3. Có kiến thức về [python](https://python.org) và [django](https://docs.djangoproject.com/en/2.2/) hoặc tài liệu khóa học tiếng việt của mình [tại đây](https://www.youtube.com/playlist?list=PLZEIt444jqpB1j3RD4BrYm9JmNVYuzVNm)
4. Có kiến thức về  [Restful API](https://www.django-rest-framework.org/tutorial/quickstart/)
5. Có kiến thức về  csdl và sử dụng các hệ quản trị like mysql, [postgresql](https://www.postgresql.org/docs/10/index.html)
6. config nginx and deploy webserver

### Đối với front end 

1. Có kiến thức về HTML, CSS, javascript. Tối thiểu phải học layout [trang này](https://www.w3schools.com/css/tryit.asp?filename=trycss_website_layout_blog)
2. Có kiến thức về  [Typescript](https://www.typescriptlang.org/docs/handbook/basic-types.html)
3. Angular 7 [Tài liệu tại đây](https://angular.io/start)
4. Hiểu về api và thao tác với API web server, xác thực và phân quyền với JWT
5. Css lib boostrap 4

### Machine learning module
Đối với những bạn join vào machine learning module các bạn cần có kiến thức về 

1. Việc auto cào dữ liệu từ các site khác bằng [scrapy](https://scrapy.org/)
2. Có kiến thức cơ bản về machine learning tối thiểu hi vọng các bạn có hiểu biết về những kiến thức [ở đây](https://www.youtube.com/playlist?list=PLZEIt444jqpBPoqtW2ARJp9ICnF3c7vJC) nếu chưa biết thì xem đi nhé
3. Xử lý, phân loại văn bản, trích chọn các từ quan trọng 
4. Có kiến thức về tiền, giao dịch, sự ảnh hưởng qua lại giữa các yếu tố  trong nền kinh tế, giữa các hàng hóa tác động qua lại với nhau. (Cái này bạn cần có thêm kiến thức về  đạo hàm cơ bản)
5. Có kiến thức về thống kê đặc biệt cần biết **law of large numbers**
6. Cần đọc tài liệu về  [chứng khoán](https://drive.google.com/open?id=10byweEWqMbzoKYEEjApWzmNFJvqp1ZLQ)

## Hướng đi của dự án 

- Ver 1: Phát triển chức năng ước tính giá trị của tiền, hàng hóa theo thời gian, ước tính lợi nhuận và rủi do, ước tính lãi xuất, rủi do 
- Ver 2: Phân tích các số liệu quá khứ một mặt hàng tác động đến chuỗi cung ứng và tác động với tỷ lệ bao nhiêu 
- Ver 3: Phân tích đám đông, hiệu ứng lan tỏa qua mạng xã hội và báo chí, tâm lý đám đông, phát hiện yếu tố ảnh hưởng đến giá cổ phiếu và ảnh hưởng bao nhiêu, dự đoán đáy và đỉnh khi 1 hoặc nhiều sự kiện sảy ra
- V




