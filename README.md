# LTH17Group1.github.io
# Giới thiệu về Hệ thống phân tán

## Hệ thống phân tán là gì?

Hệ thống phân tán (Distributed System) là tập hợp các máy tính độc lập, phối hợp với nhau để đạt được một mục tiêu chung. Các máy tính giao tiếp qua mạng và hoạt động như một hệ thống thống nhất đối với người dùng.

## Các ứng dụng của hệ thống phân tán

- **Mạng xã hội và truyền thông**: Ví dụ như Facebook, Twitter.
- **Thương mại điện tử**: Ví dụ như Amazon, Shopee.
- **Ngân hàng và tài chính**: Hệ thống giao dịch trực tuyến.
- **Trò chơi trực tuyến**: Ví dụ như PUBG, Liên Quân.

## Các khái niệm chính của hệ thống phân tán

### Scalability (Khả năng mở rộng)
Khả năng hệ thống xử lý khối lượng công việc tăng lên bằng cách thêm tài nguyên.

### Fault Tolerance (Khả năng chịu lỗi)
Hệ thống tiếp tục hoạt động ngay cả khi một số thành phần gặp lỗi.

### Availability (Tính sẵn sàng)
Hệ thống luôn sẵn sàng phục vụ người dùng.

### Transparency (Tính trong suốt)
Người dùng không cần biết hệ thống được tổ chức như thế nào ở bên trong.

### Concurrency (Tính đồng thời)
Nhiều tác vụ có thể được thực hiện đồng thời.

### Parallelism (Tính song song)
Thực hiện nhiều công việc cùng lúc để cải thiện tốc độ xử lý.

### Openness (Tính mở)
Hệ thống sử dụng các tiêu chuẩn mở, cho phép tích hợp dễ dàng.

### Vertical Scaling (Mở rộng theo chiều dọc)
Nâng cấp phần cứng cho một máy chủ đơn lẻ (thêm RAM, CPU).

### Horizontal Scaling (Mở rộng theo chiều ngang)
Thêm nhiều máy chủ mới để chia sẻ tải.

### Load Balancer (Cân bằng tải)
Phân phối lưu lượng hoặc yêu cầu giữa các máy chủ để tối ưu hiệu suất.

### Replication (Sao chép)
Tạo nhiều bản sao dữ liệu để tăng tính sẵn sàng và khả năng phục hồi.

## Ví dụ: Hệ thống thương mại điện tử

Giả sử một nền tảng thương mại điện tử lớn như Amazon:

- **Scalability**: Tăng số lượng máy chủ khi có nhiều đơn hàng.
- **Fault Tolerance**: Khi một server chết, các server khác tự động tiếp nhận.
- **Availability**: Dịch vụ luôn trực tuyến, hạn chế tối đa downtime.
- **Transparency**: Người dùng không thấy được máy chủ nào xử lý yêu cầu.
- **Concurrency & Parallelism**: Xử lý đồng thời nhiều giao dịch, tìm kiếm sản phẩm.
- **Openness**: Tích hợp với các cổng thanh toán, vận chuyển bên thứ ba.
- **Vertical & Horizontal Scaling**: Mở rộng máy chủ theo cả 2 chiều.
- **Load Balancer**: Cân bằng lưu lượng truy cập đến nhiều server.
- **Replication**: Dữ liệu đơn hàng và sản phẩm được sao lưu trên nhiều trung tâm dữ liệu.

## Kiến trúc của hệ thống phân tán

### Kiến trúc Client-Server
- Máy khách gửi yêu cầu, máy chủ xử lý.
- Ví dụ: Trình duyệt web và server web.

### Kiến trúc Peer-to-Peer (P2P)
- Mỗi node vừa là client vừa là server.
- Ví dụ: BitTorrent.

### Kiến trúc Microservices
- Ứng dụng chia thành các dịch vụ nhỏ, độc lập.
- Ví dụ: Netflix.

### Kiến trúc Service-Oriented Architecture (SOA)
- Dịch vụ giao tiếp với nhau qua các chuẩn như SOAP.

### Kiến trúc Event-Driven
- Các thành phần giao tiếp thông qua sự kiện, phù hợp hệ thống thời gian thực.

## Ví dụ: Hệ thống Hadoop

Hadoop cho phép xử lý dữ liệu lớn bằng cách:

- **Scalability**: Thêm node vào cluster để mở rộng xử lý.
- **Fault Tolerance**: Dữ liệu được sao lưu nhiều bản trên các node khác nhau.
- **Parallelism**: Các node xử lý dữ liệu song song.
- **Transparency**: Người dùng không cần biết dữ liệu được xử lý ở đâu.

---

> **Nguồn tham khảo**: Slide bài giảng Hệ thống phân tán, Google, tài liệu kiến trúc hệ thống thực tế như Netflix, Amazon

