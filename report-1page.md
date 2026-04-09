# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Cơ sở dữ liệu lưu trữ điểm và thông tin sinh viên.
- Tài khoản đăng nhập của giảng viên và quản trị hệ thống.

**CIA mapping:**
- Sự cố A -> Availability  
- Sự cố B -> Integrity  
- Sự cố C -> Confidentiality  

**Phân tích sự cố B:**
- Threat: Người dùng nội bộ hoặc hacker thay đổi dữ liệu điểm trái phép.
- Vulnerability: Hệ thống phân quyền truy cập chưa chặt chẽ hoặc tài khoản bị lộ mật khẩu.
- Mitigation: Áp dụng kiểm soát truy cập chặt chẽ, ghi log thay đổi dữ liệu và sao lưu database định kỳ.
### 4. Kết luận ngắn
Qua bài lab này em hiểu rõ hơn về mô hình CIA trong bảo mật thông tin. Ba yếu tố Confidentiality, Integrity và Availability đều rất quan trọng trong việc bảo vệ hệ thống thông tin. Việc phân tích threat, vulnerability và mitigation giúp xác định nguyên nhân và đưa ra giải pháp để giảm thiểu rủi ro. Phần khó nhất là xác định đúng loại CIA cho từng sự cố. Khi phân tích một sự cố an toàn thông tin cần xem xét cả nguyên nhân, lỗ hổng và giải pháp để bảo vệ hệ thống tốt hơn.
