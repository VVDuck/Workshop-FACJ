---
title: "Worklog Tuần 2"
date: 2024-01-08
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2

* Làm quen với AWS Management Console.
* Cài đặt và cấu hình AWS CLI.
* Nắm được các lệnh cơ bản của AWS CLI.
* Thực hành quản lý tài nguyên AWS bằng cả Console và CLI.
* Hoàn thành các bài Lab cơ bản về AWS CLI.

### Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Ôn tập AWS Global Infrastructure và IAM.<br>- Khám phá AWS Management Console.<br>- Tìm hiểu cách tìm kiếm và truy cập các dịch vụ AWS.<br>- Làm quen với Dashboard và các nhóm dịch vụ trên Console. | 24/04 | 24/04 | https://cloudjourney.awsstudygroup.com/ |
| 3 | - Cài đặt AWS CLI trên Windows/Linux.<br>- Cấu hình AWS CLI bằng lệnh `aws configure`.<br>- Tìm hiểu Access Key, Secret Access Key và Region mặc định.<br>- Kiểm tra kết quả cài đặt. | 25/04 | 25/04 | Lý thuyết: https://cloudjourney.awsstudygroup.com/<br>Thực hành: YouTube FCJ Bootcamp 2025 - AWS CLI Installation Lab |
| 4 | - Học các lệnh AWS CLI thông dụng.<br>&emsp;+ aws configure list<br>&emsp;+ aws sts get-caller-identity<br>&emsp;+ aws ec2 describe-regions<br>&emsp;+ aws ec2 describe-instances<br>&emsp;+ aws iam list-users | 26/04 | 26/04 | Lý thuyết: https://cloudjourney.awsstudygroup.com/<br>Thực hành: YouTube FCJ Bootcamp 2025 - AWS CLI Basic Commands Lab |
| 5 | - Thực hành tạo và quản lý EC2 Key Pair bằng CLI.<br>- Tìm hiểu các định dạng đầu ra của AWS CLI (json, yaml, table, text).<br>- Tìm hiểu tài liệu Help của AWS CLI.<br>- Thực hành lọc kết quả trả về của câu lệnh. | 27/04 | 27/04 | YouTube FCJ Bootcamp 2025 - AWS CLI Practice Lab |
| 6 | - Hoàn thành các bài Lab AWS CLI.<br>- Ôn tập cách kết hợp Console và CLI.<br>- So sánh việc quản lý tài nguyên bằng giao diện và dòng lệnh.<br>- Tổng kết kiến thức đã học trong tuần. | 28/04 | 28/04 | YouTube FCJ Bootcamp 2025 - AWS CLI Lab |

### Kết quả đạt được tuần 2

* Cài đặt và cấu hình thành công AWS CLI bao gồm:
  * Access Key
  * Secret Access Key
  * Region mặc định
  * Định dạng đầu ra

* Hiểu cách AWS CLI giao tiếp với các dịch vụ AWS thông qua API.

* Thực hiện được các thao tác cơ bản bằng AWS CLI:
  * Kiểm tra cấu hình hiện tại
  * Xem danh sách Region
  * Kiểm tra IAM User
  * Xem thông tin EC2
  * Quản lý EC2 Key Pair

* Biết sử dụng tài liệu hướng dẫn và hệ thống Help của AWS CLI.

* Hiểu được sự khác nhau giữa AWS Management Console và AWS CLI.

* Có khả năng quản lý tài nguyên AWS bằng giao diện web và dòng lệnh một cách linh hoạt.

* Hoàn thành toàn bộ các bài Lab cơ bản về AWS CLI.

* Xây dựng nền tảng cho việc tự động hóa quản lý hạ tầng AWS ở các tuần tiếp theo.