---
title: "Worklog Tuần 1"
date: 2026-04-20
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---


### Mục tiêu tuần 1:

* Tìm hiểu về mục đích hướng tới của chương trình, nắm rõ được nội quy khi tham gia chương trình. 
* Tìm hiểu, kết nối, làm quen với các thành viên trong First Cloud AI Journey.
* Hiểu được các dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   |  ***Module 01-01 - Introduction to AWS:** <br>&emsp; - Nắm vững các thành phần hạ tầng cốt lõi: Data Center, Availability Zone (AZ), Region, và Edge Location/Local Zone. <br> ***Module 01-02 - Management Console:** <br>&emsp; - Phân biệt rõ sự khác biệt quyền hạn giữa Root Account và IAM User. <br>&emsp; - Nắm bắt 3 phương thức tương tác chính với AWS: Management Console, CLI và SDK. <br> ***Module 01-03 - Gen AI on AWS - Kiro:** <br>&emsp; - Tìm hiểu sự chuyển dịch sang Agentic AI và phương pháp Spec-Driven Development. <br>&emsp; - Khám phá bộ công cụ Kiro IDE, Kiro CLI và cách tạo các Custom Agents chuyên biệt. <br> ***Module 01-04 - Cost Optimization on AWS:** <br>&emsp; - Hiểu rõ chiến lược Right-sizing, so sánh các mô hình trả phí (On-demand, Spot, Saving Plans) và ưu thế tối ưu hóa của kiến trúc Serverless. <br>&emsp; - Tìm hiểu 4 mức độ AWS Support (Basic, Developer, Business, Enterprise) và tiêu chuẩn đánh giá hệ thống qua AWS Well-Architected Framework. | 04/20/2026 | 04/20/2026      | ***Module 01-01:** <br> https://www.youtube.com/watch?v=qVCF7UjYC5s <br> ***Module 01-02:** <br> https://www.youtube.com/watch?v=95quNuhvMT0 <br> ***Module 01-03:** <br> https://www.youtube.com/watch?v=uAQCm4sm_1c <br> ***Module 01-04:** <br> https://www.youtube.com/watch?v=UIw8UxGZCHA
| 3   | * Hiểu rõ 6 Trụ cột kiến trúc: Bảo mật, Vận hành xuất sắc, Độ tin cậy, Hiệu suất, Tối ưu chi phí và Bền vững. <br> * Làm quen với AWS Well-Architected Tool để thực hiện đánh giá rủi ro dự án thực tế trên Console. | 21/04/2026   | 21/04/2026     | |
| 4   | ***Lab000001: Creating Your First AWS Account** <br>&emsp; - Khởi tạo tài khoản AWS và lập tức kích hoạt Xác thực Đa yếu tố (MFA) cho tài khoản Root. <br>&emsp; - Tạo nhóm quyền quản trị (Admins) và người dùng IAM chuyên trách (ductin-admin). <br> ***Lab000009: Getting Help with AWS Support** <br>&emsp; - Phân tích và so sánh 4 cấp độ hỗ trợ của AWS (Basic, Developer, Business, Enterprise) áp dụng cho các kịch bản môi trường khác nhau. | 22/04/2026   | 22/04/2026      | ***Lab000001: Creating Your First AWS Account** <br> https://000001.awsstudygroup.com/ <br> ***Lab000009: Getting Help with AWS Support** <br> https://000009.awsstudygroup.com/  |
| 5   | ***Lab000007: Managing Costs with AWS Budgets** <br>&emsp; - Thiết lập Expense Budget: Khởi tạo giới hạn an toàn (trần chi phí). <br>&emsp; - Thiết lập Preset Budget: Hệ thống sẽ báo động ngay lập tức nếu phát sinh cước phí dù chỉ 1 xu ($0.01) <br>&emsp; - Thiết lập Usage Budget: Theo dõi sát sao thời lượng hoạt động (runtime) của các dịch vụ cốt lõi như EC2.| 23/04/2026   | 23/04/2026      | ***Lab000007: Managing Costs with AWS Budgets** <br> https://000007.awsstudygroup.com/|
| 6   | ***Lab000180: Kiro Spec Driven Development** <br>&emsp; - Cài đặt IDE Kiro và tìm hiểu các khả năng của Kiro| 24/04/2026   | 24/04/2026     |  |


### Kết quả đạt được tuần 1:

1. Hiểu nền tảng về AWS
* Nắm vững kiến trúc hạ tầng toàn cầu của AWS (Regions, AZs, Edge Locations).
* Triển khai thành công môi trường AWS an toàn: Kích hoạt Xác thực đa yếu tố (MFA) cho tài khoản Root ngay khi khởi tạo; thiết lập nhóm quản trị (Admins) và người dùng IAM chuyên trách (ductin-admin), đảm bảo tuân thủ nghiêm ngặt nguyên tắc Đặc quyền tối thiểu (Least Privilege).

2. Biết cách thiết lập các Budget phù hợp theo nhu cầu và dịch vụ
* Thấu hiểu các chiến lược Tối ưu hóa chi phí (Right-sizing, Serverless architectures) và đánh giá các mô hình định giá của AWS.
* Thiết lập thành công "Hệ thống cảnh báo sớm" (Billing IDS) thông qua AWS Budgets: Cấu hình trần chi phí (Expense Budget), cảnh báo tức thời khi phát sinh cước dù chỉ $0.01 (Preset Budget), và giám sát thời lượng chạy của EC2 (Usage Budget) để phòng chống rủi ro tài chính do chiếm đoạt tài khoản.

3. Tìm hiểu về AWS Well-Architected Framework và Support Center
* Hiểu rõ 6 trụ cột (Pillars) của AWS Well-Architected Framework.
* Thực hành sử dụng công cụ AWS Well-Architected Tool trên Console để đánh giá rủi ro hệ thống thực tế. Phân tích và lập bản đồ 4 gói AWS Support để sẵn sàng cho quy trình leo thang xử lý sự cố khẩn cấp.

4. Tìm hiểu về Kiro
* Tiếp cận tư duy phát triển hiện đại với phương pháp Spec-Driven Development (SDD) và Agentic AI.
* Hoàn tất cài đặt và làm quen với môi trường Kiro IDE (Amazon Q).


