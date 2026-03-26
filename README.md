# Nhom5-web-ban-kinh-testing
Nhom 5 KTPM 3/2026
# WEB BÁN KÍNH - SOFTWARE TESTING PROJECT

## Giới thiệu
Dự án kiểm thử phần mềm cho hệ thống **Website bán kính mắt**, được thực hiện môn *Kiểm thử phần mềm*.  
Nhóm áp dụng phương pháp **kiểm thử hộp đen** để đánh giá các chức năng của hệ thống dựa trên dữ liệu đầu vào và kết quả đầu ra.

---

## Mục tiêu dự án
- Áp dụng kỹ thuật kiểm thử hộp đen vào hệ thống thực tế
- Thiết kế Test Case dựa trên yêu cầu chức năng
- Phát hiện lỗi thông qua kiểm thử đầu vào/đầu ra
- Đánh giá mức độ đáp ứng yêu cầu của hệ thống
---

## Thành viên nhóm

| STT | Họ tên | Vai trò |
|-----|--------|---------|
| 1 | Mẫn Bá Tuấn Thành | Tester |
| 2 | Trương Tôn Thiện Anh | Tester |
| 3 | Nguyễn Mạnh Hưng | Tester |
| 4 | Nguyễn Tuấn Minh | Tester |

---

## Phạm vi kiểm thử

Các chức năng chính của hệ thống:

- Đăng ký tài khoản  
- Đăng nhập / Đăng xuất  
- Quản lý tài khoản  
- Đặt mua sản phẩm  
- Quản lý danh mục  

---

## Phương pháp kiểm thử

Nhóm sử dụng **Black-box Testing**:

- Kiểm thử dựa trên:
  - Dữ liệu đầu vào (Input)
  - Kết quả đầu ra (Output)

### Kỹ thuật áp dụng
- Phân lớp tương đương (Equivalence Partitioning)
- Phân tích giá trị biên (Boundary Value Analysis)
- Bảng quyết định (Decision Table)

---

## Quy trình kiểm thử phần mềm

Quy trình kiểm thử được xây dựng theo giáo trình môn *Nhập môn Công nghệ phần mềm*:

### Bước 1: Thiết kế Test Case
- Xây dựng các ca kiểm thử dựa trên yêu cầu hệ thống

### Bước 2: Chuẩn bị dữ liệu kiểm thử
- Chuẩn bị dữ liệu đầu vào hợp lệ và không hợp lệ

### Bước 3: Thực hiện kiểm thử
- Thực thi các test case trên hệ thống

### Bước 4: So sánh và đánh giá kết quả
- So sánh kết quả thực tế với kết quả mong đợi

### Bước 5: Báo cáo kiểm thử
- Ghi nhận lỗi và lập báo cáo

---

## Các cấp độ kiểm thử

### Unit Testing
- Kiểm thử từng chức năng riêng lẻ  
(Ví dụ: form đăng ký, form đăng nhập)

### Integration Testing
- Kiểm thử sự tương tác giữa các chức năng  
(Ví dụ: Đăng ký → Đăng nhập)

### System Testing
- Kiểm thử toàn bộ hệ thống hoàn chỉnh  

### Acceptance Testing
- Kiểm thử chấp nhận từ phía người dùng  

**Bao gồm:**
- Alpha Testing (môi trường kiểm soát)
- Beta Testing (môi trường thực tế)

---

## Cấu trúc thư mục
/docs
test-plan.md
test-case.xlsx
/src
/reports
test-report.md
README.md

---

## Kế hoạch thực hiện

| Giai đoạn | Nội dung |
|-----------|----------|
| Tuần 1 | Phân tích yêu cầu |
| Tuần 2 | Thiết kế Test Case |
| Tuần 3 | Thực hiện kiểm thử |
| Tuần 4 | Tổng hợp và báo cáo |

---

## Quản lý lỗi

Sử dụng GitHub Issues để:
- Ghi nhận lỗi (Bug)
- Theo dõi tiến độ xử lý
- Phân công công việc

---

## Kết quả mong đợi
- Phát hiện các lỗi chức năng của hệ thống  
- Đảm bảo hệ thống hoạt động đúng yêu cầu  
- Xây dựng quy trình kiểm thử rõ ràng  

---

## Ghi chú
- Tất cả thành viên tuân thủ phương pháp kiểm thử hộp đen  
- Không truy cập hoặc kiểm tra mã nguồn  
- Thực hiện kiểm thử dựa trên yêu cầu hệ thống  

---

> *Dự án phục vụ mục đích học tập môn Kiểm thử phần mềm*
