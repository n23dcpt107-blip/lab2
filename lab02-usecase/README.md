# Lab 02 - Phân tích yêu cầu & Thiết kế Use Case

## Mini Project đã chọn
ATM Mini Project (mô phỏng máy rút tiền tự động).

## Các chức năng chính
- Đăng nhập (Login)
- Rút tiền (Withdraw)
- Gửi tiền (Deposit)
- Chuyển khoản (Transfer)
- Xem số dư (Check Balance)

## Use Case Description

### 1. Rút tiền (Withdraw)
- **Actor:** Khách hàng  
- **Mục tiêu:** Khách hàng rút tiền mặt từ tài khoản  
- **Luồng chính:**
  1. Khách hàng đưa thẻ ATM và nhập PIN.
  2. Hệ thống xác thực PIN.
  3. Khách hàng nhập số tiền muốn rút.
  4. Hệ thống kiểm tra số dư.
  5. Hệ thống xuất tiền mặt.
  6. Cập nhật số dư tài khoản.

- **Ngoại lệ:**
  - PIN sai → báo lỗi, cho nhập lại.
  - Số dư không đủ → báo lỗi, hủy giao dịch.

### 2. Xem số dư (Check Balance)
- **Actor:** Khách hàng  
- **Mục tiêu:** Khách hàng muốn biết số dư hiện tại  
- **Luồng chính:**
  1. Khách hàng đưa thẻ và nhập PIN.
  2. Hệ thống xác thực PIN.
  3. Hệ thống hiển thị số dư.

- **Ngoại lệ:**
  - PIN sai → báo lỗi.
