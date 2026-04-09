# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Vũ Hồng Sơn

**MSSV:** 1871020506

**Lớp/Nhóm:** CNTT18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Cơ sở dữ liệu điểm sinh viên (Database lưu điểm, thông tin sinh viên).
- Asset 2: Tài khoản đăng nhập của giảng viên và quản trị hệ thống.
- Asset 3 (nếu có): Máy chủ hệ thống quản lý điểm.

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A -> Confidentiality
(Thông tin điểm của sinh viên bị lộ cho người không có quyền truy cập)
- Sự cố B -> Integrity
(Điểm số bị thay đổi trái phép trong hệ thống)
- Sự cố C -> Availability
(Hệ thống bị sập hoặc không truy cập được)

---

## 3. Phân tích sự cố B
- Threat:
Hacker hoặc người dùng nội bộ cố ý thay đổi điểm số trong hệ thống.
- Vulnerability:
Hệ thống phân quyền yếu, mật khẩu yếu hoặc không có kiểm tra xác thực đầy đủ.
-  Mitigation:
Áp dụng xác thực mạnh (Strong Authentication).
Phân quyền truy cập rõ ràng.
Ghi log các hoạt động thay đổi dữ liệu.
Sao lưu dữ liệu định kỳ.

## 4. Reflection
Qua bài lab này em hiểu rõ hơn về mô hình CIA trong bảo mật thông tin. Ba yếu tố Confidentiality, Integrity và Availability đều rất quan trọng trong việc bảo vệ hệ thống thông tin. Trong hệ thống lưu điểm, việc bảo mật dữ liệu, đảm bảo tính toàn vẹn của điểm số và đảm bảo hệ thống luôn hoạt động là rất cần thiết. Nếu một trong ba yếu tố bị vi phạm thì hệ thống có thể bị ảnh hưởng nghiêm trọng. Bài lab giúp em hiểu rõ hơn về các rủi ro bảo mật và cách giảm thiểu chúng.
## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`
FIT4012{A-Confidentiality-B-Integrity-C-Availability}

Flag của em:

FIT4012{A-Confidentiality-B-Integrity-C-Availability}
