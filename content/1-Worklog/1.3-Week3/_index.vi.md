---
title: "Worklog Tuần 3"
weight: 3
date: 2026-05-05
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3

* Hiểu các kiến thức cơ bản về Amazon EC2.
* Tìm hiểu các loại EC2 Instance và mô hình tính phí.
* Thực hành tạo và quản lý EC2 Instance.
* Kết nối đến EC2 bằng SSH.
* Thực hiện các thao tác quản lý EC2 cơ bản.

### Các công việc cần triển khai trong tuần này

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2 | - Tìm hiểu tổng quan về Amazon EC2.<br>&emsp;+ Amazon EC2 là gì?<br>&emsp;+ Các trường hợp sử dụng EC2.<br>&emsp;+ Vòng đời của EC2 Instance.<br>&emsp;+ Shared Responsibility Model đối với EC2. | 01/05 | 01/05 | https://www.youtube.com/watch?v=e7XeKdOVq40&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=73 |
| 3 | - Tìm hiểu các thành phần của EC2.<br>&emsp;+ Instance Types.<br>&emsp;+ Amazon Machine Image (AMI).<br>&emsp;+ Security Group.<br>&emsp;+ Key Pair.<br>&emsp;+ EBS Volume.<br>&emsp;+ Elastic IP. | 02/05 | 02/05 | https://www.youtube.com/watch?v=yAR6QRT3N1k&list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i&index=74 |
| 4 | - Thực hành tạo EC2 Instance.<br>- Cấu hình Security Group.<br>- Tạo và tải Key Pair.<br>- Gắn EBS Volume.<br>- Kiểm tra trạng thái EC2. | 03/05 | 03/05 | https://000003.awsstudygroup.com/4-createec2server/ |
| 5 | - Thực hành kết nối SSH tới EC2.<br>- Tìm hiểu các phương thức kết nối (EC2 Instance Connect, SSH Client, PuTTY).<br>- Kiểm tra khả năng kết nối mạng.<br>- Thực hành các lệnh Linux cơ bản trên EC2. | 04/05 | 04/05 | https://000003.awsstudygroup.com/4-createec2server/4.5-eicendpoint/ |
| 6 | - Thực hành Stop, Start, Reboot và Terminate EC2 Instance.<br>- Tìm hiểu các mô hình tính phí EC2 (On-Demand, Reserved, Spot).<br>- Ôn tập kiến thức và hoàn thành các bài Lab về EC2. | 05/05 | 05/05 | https://000003.awsstudygroup.com/6-cleanup/ |

### Kết quả đạt được tuần 3

* Hiểu kiến trúc và mục đích sử dụng của Amazon EC2.

* Nắm được các thành phần quan trọng của EC2:
  * Instance Types
  * Amazon Machine Image (AMI)
  * Security Group
  * Key Pair
  * EBS Volume
  * Elastic IP

* Tạo và cấu hình thành công một EC2 Instance.

* Thiết lập Security Group để cho phép truy cập SSH.

* Kết nối thành công tới EC2 bằng giao thức SSH.

* Thực hành các lệnh Linux cơ bản trên máy chủ EC2.

* Hiểu vòng đời của EC2 Instance:
  * Launch
  * Stop
  * Start
  * Reboot
  * Terminate

* Nắm được các mô hình mua EC2:
  * On-Demand Instance
  * Reserved Instance
  * Spot Instance

* Hiểu mối liên hệ giữa EC2, EBS, Security Group và Key Pair trong quá trình triển khai máy chủ.

* Hoàn thành toàn bộ các bài Lab cơ bản về Amazon EC2.