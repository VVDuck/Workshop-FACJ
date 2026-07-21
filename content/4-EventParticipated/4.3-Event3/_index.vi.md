---
title: "Sự kiện 3"
date: 2026-05-23
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# Bài thu hoạch “AWS First Cloud AI Journey — Community Day”

### Thông tin sự kiện
| | |
|---|---|
| **Event Name** | AWS First Cloud AI Journey — Community Day |
| **Date** | 23/05/2026 |
| **Location** | 26th Floor, Bitexco Financial Tower, 2 Hai Trieu Street, Ben Nghe Ward, District 1, Ho Chi Minh City |
| **Organizer** | AWS Study Group |
| **Role** | Participant / Intern |

### Mục Tiêu Sự Kiện

- Ghi lại các bài học thực tiễn từ 5 chuyên đề nổi bật về context engineering, kiểm toán GenAI, kiểm soát chi phí CloudFront, hackathon 36 giờ, tính phi tất định của LLM và mô hình multi-agent.
- Tái hiện mối liên hệ giữa GenAI, DevOps, platform engineering và bảo mật Cloud trong các dự án AWS thực tế.
- Tổng hợp những kiến thức kỹ thuật và bài học kinh doanh có thể áp dụng cho việc học tập của em và cho dự án LingoRise.
- Lưu lại những trao đổi trực tiếp và kết nối với các chuyên gia đám mây, mentor và diễn giả tại sự kiện.

### Danh Sách Diễn Giả

- **Tinh Truong** – Platform Engineer, GoTymeX
- **Pham Nguyen Hai Anh** – Cloud Consultant tại G-AsiaPacific Vietnam, AWS Community Builder - Security
- **Nguyen Tuan Thinh** – DevOps Engineer, First Cloud AI Journey
- **Team VIB** – Nhóm GenAI và phát triển phần mềm của VIB
- **Duc Dao** – Solution Architect, Cloud Kinetics
- **Vy Lam** – Senior Business Systems Analyst, VPBank

### Nội Dung Nổi Bật

#### Context Is Everything — Making AI Actually Work for You

Trình bày bởi diễn giả **Tinh Truong** (Platform Engineer, GoTymeX), chuyên đề tập trung vào tầm quan trọng cốt lõi của "ngữ cảnh" (context) khi làm việc với mô hình ngôn ngữ lớn (LLM).

- AI sẽ thất bại nếu thiếu ngữ cảnh: dù mô hình rất mạnh, đầu ra vẫn mơ hồ và thiếu thực tế nếu đầu vào quá sơ sài.
- Context là toàn bộ thông tin giúp AI hiểu rõ "nhiệm vụ ẩn sau nhiệm vụ".
- Ngữ cảnh chất lượng gồm mục tiêu, tình huống, ràng buộc và bằng chứng liên quan.
- Sai lầm phổ biến là vấn đề "Internet Puller", tức là chép quá nhiều tài liệu, PDF, ảnh chụp màn hình và ghi chú thô vào một ô chat duy nhất.
- Ngữ cảnh thừa nhưng không liên quan sẽ làm AI bị nhiễu, giảm độ chính xác và tăng chi phí token.
- Mô hình "Bộ não AI thứ hai" cho thấy cách kết hợp giữa ngữ cảnh và trí nhớ để hỗ trợ học tập và trả lời tốt hơn.

#### GenAI-Powered Auto Audit for AWS Workload

Trình bày bởi diễn giả **Pham Nguyen Hai Anh** (Cloud Consultant tại G-AsiaPacific Vietnam, AWS Community Builder - Security), chuyên đề giới thiệu giải pháp tự động hóa kiểm định hệ thống thông qua các trợ lý GenAI, giải quyết các khó khăn thường nhật của doanh nghiệp.

- Người dùng nghiệp vụ thường gặp khó khăn khi phải tìm kiếm dữ liệu thủ công từ nhiều nguồn rời rạc, phụ thuộc vào chuyên gia để phân tích sâu và lặp lại các công việc tốn thời gian.
- Amazon Q Business (Quick Suite) được phân tích như một mô hình đa tác vụ gồm Insights, BI & Automation, tích hợp nguồn dữ liệu và lớp bảo mật/kiểm soát.
- Nền tảng có thể kết nối hơn 40 cổng dữ liệu doanh nghiệp như Google Workspace, S3 và databases, đồng thời vẫn duy trì phân quyền chặt chẽ.
- Use case PM Assistant cho thấy cách trợ lý ảo tự động tạo biên bản họp từ file ghi âm, gửi email cập nhật và sắp xếp lịch họp tiếp theo.
- Chuyên đề cũng minh họa cách dùng LLM để quét kiến trúc AWS, đối chiếu tiêu chuẩn bảo mật và phát hiện lỗ hổng hệ thống.

#### From Edge to Origin: CloudFront as Your Foundation

Trình bày bởi diễn giả **Nguyen Tuan Thinh** (DevOps Engineer, First Cloud AI Journey), chuyên đề khai thác vai trò của Amazon CloudFront như một lớp phân phối nền tảng, đồng thời phân tích các rủi ro tài chính liên quan đến chi phí CDN trên đám mây.

- CloudFront hoạt động như chốt chặn đầu tiên để cache và phân phối tài nguyên tĩnh/động từ các Edge Location toàn cầu, giúp giảm độ trễ.
- Mô hình pay-as-you-go có thể khó dự báo vì lưu lượng truy cập thay đổi liên tục.
- Khi ứng dụng viral hoặc bị tấn công DDoS, hóa đơn CDN có thể tăng vọt ngoài tầm kiểm soát.
- Chuyên đề nêu rõ rủi ro tài chính khi hóa đơn đám mây tăng bất ngờ lên mức rất lớn đối với nhà sáng lập.
- Các thực hành tốt nhất gồm CloudWatch Billing Alerts, AWS WAF và tối ưu chính sách TTL để nâng cao tỷ lệ hit-ratio cache.

#### 36 hrs with LotusHacks: Building UTMorpho from Idea to Reality

Trình bày bởi **Team VIB** (đại diện nhóm kỹ sư GenAI và phát triển phần mềm của VIB), chuyên đề chia sẻ về trải nghiệm thực tế đầy áp lực khi tham gia cuộc thi hackathon LotusHacks kéo dài 36 giờ để xây dựng và ra mắt sản phẩm **UTMorpho**.

- Hành trình bắt đầu từ "Giờ thứ 0" khi đầu óc còn trống rỗng và dần hình thành ý tưởng từ những vấn đề thực tế quan sát được trong ngày khai mạc.
- Quy trình chạy nước rút 36 giờ được chia thành: Setup & Alignment, First Slice, Build the core, The hard middle, Integration & Polish, và Submit & Pitch.
- Chuyên đề nhấn mạnh việc xác định MVP nhanh, chốt ranh giới API sớm và giữ cho cả nhóm luôn đồng thuận dưới áp lực thời gian.
- Bài học lớn là phải quản lý technical debt linh hoạt, tạo prototype nhanh và tập trung giải quyết một vấn đề thật tốt thay vì cố gắng nhồi quá nhiều tính năng.

#### Non-Determinism of 'Deterministic' LLM Settings

Trình bày bởi diễn giả **Duc Dao** (Solution Architect - Cloud Kinetics), chuyên đề đi sâu nghiên cứu cơ chế chọn lựa token của LLM, các thiết lập lấy mẫu (sampling), và lý do thực tế tại sao cài đặt Temperature = 0 vẫn không đảm bảo tính nhất quán (deterministic) hoàn toàn ở đầu ra.

- LLM sinh văn bản theo từng token bằng cách tính logits, áp dụng softmax và chọn token tiếp theo từ phân phối xác suất.
- Temperature điều khiển độ phân tán của phân phối; về lý thuyết, Temperature = 0 sẽ luôn chọn token có xác suất cao nhất.
- Trên thực tế, xử lý song song trên GPU vẫn có thể tạo ra khác biệt nhỏ do phép cộng dấu phẩy động không có tính kết hợp.
- Tải hệ thống, cân bằng tải và sự khác biệt phần cứng giữa các cloud provider cũng có thể làm thay đổi kết quả đôi chút.
- Chuyên đề khuyến nghị validation JSON schema nghiêm ngặt, ràng buộc chặt hơn trong system prompt, sử dụng seed và xây dựng parser backend để xử lý ngoại lệ.

#### Enterprise-Grade Multi-Agent System: The Case of Startup Credit Scoring

Trình bày bởi diễn giả **Vy Lam** (Senior Business Systems Analyst, VPBank), chuyên đề phân tích rào cản hệ thống khi đánh giá tín dụng doanh nghiệp khởi nghiệp và mô hình AI Multi-Agent khắc phục các nhược điểm của Single-Agent.

- Ngân hàng truyền thống thường yêu cầu báo cáo tài chính 3+ năm, tài sản thế chấp và doanh thu ổn định, trong khi startup chỉ có lịch sử hoạt động ngắn hơn nhiều.
- Startup thường dựa vào sở hữu trí tuệ và chỉ số tăng trưởng nên dễ bị loại bởi mô hình duyệt tín dụng cứng nhắc dù có tiềm năng.
- Một single-agent duy nhất sẽ gặp giới hạn ngữ cảnh, loãng chuyên môn, thiếu cơ chế kiểm soát chéo và có nguy cơ trở thành single point of failure.
- Mô hình multi-agent được đề xuất như một "hội đồng tín dụng ảo" với các agent chuyên biệt cho tài chính, công nghệ/IP và kiểm toán rủi ro.
- Lớp bảo vệ doanh nghiệp được mô tả qua 5 tầng: Perimeter, mạng VPC, Identity, Application và Data.

### Những Gì Học Được

#### Context Engineering

- Ngữ cảnh sạch và chọn lọc là yếu tố then chốt để AI cho ra kết quả tốt.
- Context biến một yêu cầu mơ hồ thành một bài toán có thể giải quyết được.
- Sự kết hợp giữa ngữ cảnh và trí nhớ chính là cách tạo ra một "bộ não AI thứ hai" hữu ích trong thực tế.

#### GenAI và Tự Động Hóa

- GenAI có thể giảm công việc lặp lại bằng cách tự động ghi chú, truy xuất dữ liệu và kiểm định hệ thống.
- Quy trình doanh nghiệp trở nên thực tế hơn khi AI được kết nối với dữ liệu thật của tổ chức.

#### Kiến Trúc Cloud và Kiểm Soát Chi Phí

- CloudFront giúp giảm độ trễ nhưng việc sử dụng CDN phải được giám sát chặt chẽ.
- Billing alerts, WAF và tối ưu TTL là các biện pháp vận hành rất quan trọng.
- Chi phí cloud tăng bất ngờ có thể trở thành rủi ro nghiêm trọng nếu không có kiểm soát.

#### Phát Triển Trong Hackathon

- Prototype nhanh và phạm vi MVP rõ ràng là yếu tố sống còn khi thời gian rất hạn chế.
- Lỗi tích hợp là điều bình thường ở giai đoạn giữa nên cả nhóm phải giữ được sự đồng thuận.
- Tập trung giải quyết tốt một vấn đề còn hiệu quả hơn việc cố gắng làm quá nhiều tính năng.

#### Hành Vi LLM Phi Tất Định

- Temperature = 0 không đảm bảo tính deterministic tuyệt đối trong môi trường GPU thực tế.
- Validation backend và parser fallback là cần thiết khi output của model có thể thay đổi định dạng.
- Kiểm tra schema chặt chẽ và ràng buộc prompt tốt hơn sẽ giảm lỗi downstream.

#### Multi-Agent AI và Bảo Mật Doanh Nghiệp

- Chia các tác vụ AI phức tạp thành các agent chuyên biệt sẽ bền vững hơn so với nhét tất cả vào một model lớn.
- Hệ thống AI cấp doanh nghiệp cần kiểm soát theo nhiều lớp ở network, identity, application và data.
- Chống prompt injection và rate limiting là các yếu tố quan trọng để triển khai an toàn.

### Ứng Dụng Vào Công Việc

- Sử dụng context sạch và chọn lọc khi làm việc với AI hỗ trợ lập trình hoặc thiết kế prompt.
- Tiếp tục tách LingoRise thành luồng tạo đề thi và luồng chấm điểm Writing riêng biệt.
- Duy trì bộ parser fallback `extractJsonObject()` để xử lý JSON lỗi từ output của LLM.
- Áp dụng kiểm tra biên API, chống prompt injection và rate limiting để bảo vệ các tính năng tương lai.
- Dùng CloudFront OAC, billing alerts và tối ưu TTL để tăng độ an toàn và khả năng dự đoán chi phí cho tài nguyên cloud.
- Thiết kế các tính năng cấp doanh nghiệp theo tư duy multi-agent khi bài toán quá phức tạp để một AI step xử lý một mình.

### Trải Nghiệm Trong Event

Tham gia sự kiện **AWS First Cloud AI Journey — Community Day** giúp em có cái nhìn rộng hơn về cách các ý tưởng cloud, GenAI và bảo mật liên kết với nhau trong các dự án thực tế.

#### Học hỏi từ các chuyên đề thực tế

- Chuyên đề về context giúp em hiểu rằng câu trả lời của AI sẽ tốt hơn khi prompt được viết rõ ràng và có phạm vi cụ thể.
- Chuyên đề GenAI auto-audit cho thấy quy trình doanh nghiệp có thể được tự động hóa bằng AI và dữ liệu kết nối thực tế.
- Chuyên đề CloudFront làm rõ sự đánh đổi giữa khả năng mở rộng dễ dàng và nguy cơ chi phí tăng khó lường.

#### Bài học thực tiễn

- Bài nói về LotusHacks cho thấy cách chuyển từ ý tưởng sang prototype nhanh dưới áp lực.
- Bài nói về LLM phi tất định khẳng định vì sao validation chặt và parser fallback là quan trọng trong hệ thống production.
- Bài nói về credit scoring multi-agent nhấn mạnh giá trị của phân rã, chuyên môn hóa và bảo mật theo lớp.

#### Bài học rút ra

- Chất lượng ngữ cảnh ảnh hưởng trực tiếp đến chất lượng output của AI.
- AI doanh nghiệp nên được thiết kế theo mô hình các thành phần phối hợp với nhau, thay vì một mô hình khổng lồ duy nhất.
- Bảo mật, kiểm soát chi phí và độ tin cậy phải được xem xét đồng thời trong hệ thống cloud.
- Quy trình triển khai rõ ràng giúp dễ ship được công việc có ý nghĩa ngay cả khi bị áp lực thời gian.

#### Một số hình ảnh khi tham gia sự kiện

![](/images/event/event3-1.jpg)

> Tổng thể, sự kiện giúp em hiểu sâu hơn về context engineering, tự động hóa GenAI, kiểm soát chi phí CDN trên cloud, cách triển khai hackathon, hành vi phi tất định của LLM và thiết kế hệ thống multi-agent. Đây cũng là những kiến thức rất hữu ích cho quá trình học tập của em và cho việc tiếp tục phát triển LingoRise.
