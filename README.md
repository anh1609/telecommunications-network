# Nội dung
1. [QoE Management : Dịch vụ viễn thông và quá trình chuyển đổi sang Experience Economy](#qoe-management--dịch-vụ-viễn-thông-và-quá-trình-chuyển-đổi-sang-experience-economy)

2. [CEM: Xu hướng mới trong mạng OAM](#cem-xu-hướng-mới-trong-mạng-oam)

3. [Sự chuyển đổi từ OAM tập trung vào mạng lưới sang lấy khách hàng làm trung tâm](#sự-chuyển-đổi-từ-oam-tập-trung-vào-mạng-lưới-sang-lấy-khách-hàng-làm-trung-tâm)

4. [CEMC từ đầu đến cuối](#cemc-từ-đầu-đến-cuối)

5. [Đánh giá QoE từ đầu đến cuối](#đánh-giá-qoe-từ-đầu-đến-cuối)

6. [Hoàn thành các chức năng OAM](#hoàn-thành-các-chức-năng-oam)

7. [Kiến trúc triển khai có thể mở rộng](#kiến-trúc-triển-khai-có-thể-mở-rộng)


### QoE Management : Dịch vụ viễn thông và quá trình chuyển đổi sang Experience Economy

Do cạch tranh thì trường ngày càng gay gắt, để đáp ứng nhu cầu của người dùng thì  chất lượng trải nghiệm (QoE)  là chìa khóa cho các dịch vụ viễn thông thành công

Thách thức mà các nhà khai thác phải đối mặt ngày nay là làm thế nào để giám sát và cải thiện QoS trong thời gian thực và cung cấp các dịch vụ khác biệt tùy chỉnh. Quản lý trải nghiệm khách hàng (CEM) là điều cần thiết.

### CEM: Xu hướng mới trong mạng OAM


**KPI mạng cao không nhất thiết có nghĩa là QoE tốt**

Cấu trúc quản lý kiểu ống khói thẳng đứng thường được sử dụng để vận hành và bảo trì mạng (OAM)

một số mạng chuyên dụng  có hệ thống quản lý phần tử độc quyền riêng (EMS) để đảm bảo tính khả dụng của mạng và QoS là 

   *  mạng truy cập vô tuyến (RAN),
   *  mạng lõi (CN)
   *  mạng mang

  ![hình 1](https://res-www.zte.com.cn/mediares/magazine/publication/tech_en/article/201203/307247/W020120521638501459265.jpg?la=en)     **hình 1**
  
  Ta thấy KPI cho các mạng mang CN, RAN và IP là rất cao:
  cho thấy chất lượng mạng rất tốt nhưng chất lượng cuộc gọi còn thấp
  
### Sự chuyển đổi từ OAM tập trung vào mạng lưới sang lấy khách hàng làm trung tâm
  
  - Tất cả các nguồn lực của OAM đều tập trung vào việc cải thiện trải nghiệm của khách hàng
   
   - Quản lý QoE đang dần được coi là cốt lõi của mạng OAM
   
**Bảng 1. Sự khác biệt giữa OAM định hướng theo khách hàng và mạng truyền thống theo định hướng OAM.**
![](https://res-www.zte.com.cn/mediares/magazine/publication/tech_en/article/201203/307247/W020120521638503003326.jpg?la=en)

Quản lý trải nghiệm khách hàng (CEM) là OAM mạng hướng đến khách hàng và dịch vụ. Quản lý trải nghiệm dịch vụ được phân biệt theo từng đối tượng khách hàng và dịch vụ khác nhau và là công cụ hữu hiệu để các nhà khai thác tối ưu hóa hoạt động mạng của họ.

### CEMC từ đầu đến cuối

+ Mạng OAM được tối ưu hóa bằng cách giám sát và quản lý QoE và QoS.

 + CEMC bao gồm quản lý chất lượng dịch vụ (SQM) và CEM

+ SQM thuộc quản lý QoS được sử dụng để :
     1. quản lý chất lượng dịch vụ
     2. cung cấp các chỉ số chất lượng có thể  sử dụng để theo dõi chất lượng đầu cuối của các dịch vụ khác nhau.
     
+ CEM thuộc quản lý QoE được sử dụng:
    1. đo lường QoE từ quan điểm của khách hàng.    
+  CEM được sử dụng để quản lý QoE của khách hàng

### Đánh giá QoE từ đầu đến cuối

![](https://res-www.zte.com.cn/mediares/magazine/publication/tech_en/article/201203/307247/W020120521638503088839.jpg?la=en)

+ lớp trên cùng : chỉ số trải nghiệm khách hàng (CEI).
 CEI được sử dụng để mô tả trải nghiệm dịch vụ khách hàng.
+ Lớp thứ hai: là chỉ số chất lượng chính (KQI). Cho biết hiệu suất của sản phẩm và dịch vụ .KQI có thể được tính bằng cách sử dụng các KPI khác nhau. Nó được chia thành KQI sản phẩm và KQI dịch vụ. 
+ Lớp thứ ba là KPI dựa trên mạng .Thể hiện 1 phần của dữ liệu dịch vụ  end-to-end .KPI rất quan trọng để đánh giá OAM mạng.Nó cũng là cơ sở dữ liệu cho CEI và KQI. KPI dựa trên dữ liệu cảnh báo, hiệu suất và cấu hình mạng; dữ liệu phân tích từ thăm dò chủ động / thụ động và bắt gói, và dữ liệu thanh toán.

### Hoàn thành các chức năng OAM

Mạng OAM liên quan đến việc khám phá, định vị và giải quyết các vấn đề. Ba khía cạnh này được kết nối chặt chẽ với nhau để tạo thành một hệ thống OAM mạng hoàn chỉnh
![](https://res-www.zte.com.cn/mediares/magazine/publication/tech_en/article/201203/307247/W020120521638503357522.jpg?la=en)

**hình 4 .các chức năng cốt lõi của CEMC.:**

* Việc phát hiện ra các vấn đề liên quan đến việc tìm một “nhiệt kế” thích hợp để xác định QoE của khách hàng trong thời gian thực.

* Xác định các vấn đề có nghĩa là xác định nguyên nhân có thể của vấn đề khi các bất thường được phát hiện.

* Giải quyết vấn đề có nghĩa là khắc phục các triệu chứng.

* CEMC cung cấp các chức năng OAM hoàn chỉnh giúp nhà khai thác cải thiện QoE, thiết lập cơ chế chăm sóc khách hàng, cung cấp thỏa thuận mức dịch vụ đảm bảo (SLA) và thu hút khách hàng doanh nghiệp có giá trị cao.

![](https://res-www.zte.com.cn/mediares/magazine/publication/tech_en/article/201203/307247/W020120521638503531906.jpg?la=en) 
**hình 5.Kiến trúc kết hợp của nền tảng chức năng và gói hỗ trợ dịch vụ.**

### Kiến trúc triển khai có thể mở rộng
* CEMC có một nền tảng chức năng kết hợp và gói hỗ trợ dịch vụ.

+ Các mô-đun màu xanh lam ngang trong Hình 5 đại diện cho nền tảng chức năng và các mô-đun màu vàng dọc đại diện cho gói hỗ trợ dịch vụ. 
+ có khả năng mở rộng tốt quản lý QoE phù hợp với trọng tâm quản lý dịch vụ hiện tại của nhà khai thác và nhu cầu phát triển dịch vụ trong tương lai.





   
   
 