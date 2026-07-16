# HW01 - Phân tích yêu cầu nghiệp vụ mở tài khoản ngân hàng trực tuyến (eKYC)

## Prompt sử dụng
```
Đóng vai Senior Business Analyst có 10 năm kinh nghiệm trong lĩnh vực FinTech/Ngân hàng số.
Phân tích hệ thống eKYC của ABC Bank và trả về:
- Actors
- Business Flow
- Functional Requirements
- Non-Functional Requirements
- Assumptions & Business Rules
- User Stories
- Use Cases
```

## Actors
- Khách hàng
- Hệ thống eKYC
- OCR Service
- Face Recognition Service
- Core Banking

## Business Flow
1. Đăng ký.
2. Nhập thông tin.
3. Chụp CCCD.
4. OCR.
5. Liveness Check.
6. Đối chiếu dữ liệu.
7. Tạo tài khoản.

## Functional Requirements
- Đăng ký tài khoản.
- OCR CCCD.
- Xác thực khuôn mặt.
- Sinh số tài khoản.
- Thông báo kết quả.

## Non-Functional Requirements
- TLS 1.3.
- Mã hóa AES-256.
- Response < 2 giây.
- Availability 99.9%.

## Business Rules
- CCCD gồm 12 số.
- Một CCCD chỉ mở một tài khoản.

## User Stories
- As a customer, I want to register online so that I can open an account remotely.
- As a bank, I want automated verification so that manual work is minimized.

## Use Cases
- Register
- Upload ID
- Verify Face
- Create Account
