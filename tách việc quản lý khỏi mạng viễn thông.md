# Tách việc quản lý khỏi mạng viễn thông
## Lý do cần tách phần quản lý

- TMN do đó đã tốt hơn khả năng quản lý lỗi hơn các phương pháp quản lý như OSI và SNMP.
- Thật không may, mạng lưới quản lý riêng biệt yêu cầu thiết bị bổ sung và hệ thống truyền dẫn. Chi phí do đó cao hơn. Tuy nhiên, các lỗi cũng có thể xảy ra trong mạng quản lý và do đó cũng cần phải quản lý cả mạng quản lý (quản lý meta). Điều này dẫn đến chi phí bổ sung.
- Cũng có một lý do khác để giới thiệu một mạng riêng để quản lý. Các mạng viễn thông, giống như mạng điện thoại, cung cấp một loại dịch vụ đẳng thời. Loại dịch vụ như vậy không tương ứng với loại dịch vụ không đồng bộ (hướng gói) được yêu cầu để truyền thông tin quản lý. Do đó, một mạng quản lý riêng biệt phải được giới thiệu để quản lý mạng điện thoại. Trong trường hợp đó, khả năng quản lý lỗi tốt hơn của việc phân tách chỉ là yếu tố được xem xét.
- Trái ngược với TMN, OSI và SNMP đặc biệt nhằm vào việc quản lý các mạng thông tin dữ liệu. Loại dịch vụ được cung cấp bởi các mạng này thường giống với loại dịch vụ được yêu cầu cho việc trao đổi thông tin quản lý. Với mạng thông tin dữ liệu, và do đó trong trường hợp của OSI và SNMP, cần phải xem xét nghiêm túc xem lợi ích của DCN có lớn hơn chi phí của nó hay không.
