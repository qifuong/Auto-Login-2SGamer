
# 🚀 2SGamer Auto Login 3.5

**Auto Login 3.5** là phần mềm hỗ trợ người dùng đăng nhập nhanh vào game ZingSpeed thông qua launcher 2SGamer hoặc 2SGamerQQ.  
Đây là phiên bản **chuyển hoàn toàn từ AutoIt sang Python**, với giao diện thân thiện và hiệu năng tốt hơn, cùng nhiều tính năng nâng cấp như auto login, hack speed, chỉnh FPS, dark mode và tự động cấu hình.

> 📅 **Phát hành ngày:** 11/06/2025  
> 🛠️ **Ngôn ngữ:** Python  
> 🌙 **Dark Mode:** Hỗ trợ chuyển sáng/tối

---

## 🔧 Tính Năng Chính (3.5)

- Viết lại toàn bộ từ AutoIt sang Python
- Tooltip realtime hiển thị khi dùng Hack Speed
- Cửa sổ GUI tự động căn giữa màn hình khi mở
- Tối ưu xử lý bộ nhớ: đọc/ghi trực tiếp bằng `ctypes`, không cần thư viện ngoài

---
## 🔧 Nhược Điểm (3.5)

- Tối ưu xử lý bộ nhớ chương trình chưa tốt: Chương trình hiện tại dung lượng quá cao và chiếm Ram của máy người dùng sẽ khác phục trong phiên bản sau 

## 📁 Cách Cài Đặt

1. Tải hoặc chạy `AutoLogin.exe` (nếu có bản build).
2. Ở lần đầu tiên, phần mềm yêu cầu:
   - Chọn thư mục chứa `ZingSpeedLauncher.exe`
   - Chọn thư mục 2SGamerQQ (nếu có)
   - Chọn file `accountlist.txt` chứa danh sách tài khoản (1 dòng ID, 1 dòng password)
   - Chọn loại launcher (V1 / V2)
3. Nhấn **Lưu Cấu Hình**
4. Chạy lại phần mềm và chọn tài khoản để đăng nhập

---

## 🧾 File Cấu Hình

File `setting` gồm:
```
D:\2SGamer\ZingSpeedLauncher.exe  
D:\2SGamerQQ\ZingSpeedLauncher.exe (hoặc N/A)  
V1 hoặc V2  
D:\duongdan\accountlist.txt 
```

File `accountlist.txt` ví dụ:
```
user1
pass1
user2
pass2
...
```

File `darkmode.txt`:  
- `1` = Dark Mode  
- `0` = Light Mode

---

## 🧠 Hotkeys (Khi bật Hack Mode)

| Phím         | Tác dụng                  |
|--------------|---------------------------|
| `SPACE`      | Bật hack tốc độ           |
| `F9`         | Giảm tốc độ               |
| `F10`        | Tăng tốc độ               |
| `DELETE`     | Tắt hack tốc độ           |

---

## 📜 Nhật Ký Cập Nhật

### ✅ Auto Login 3.5 (11/06/2025)

- Viết lại toàn bộ phần mềm từ AutoIt sang Python
- Thêm tooltip hiển thị realtime khi bật Hack Speed
- Bổ sung icon `.ico` cho cửa sổ giao diện và khi đóng gói `.exe`
- Căn giữa cửa sổ GUI khi mở chương trình
- Tối ưu hàm đọc/ghi bộ nhớ bằng `ctypes` (thay vì dùng thư viện ngoài)
- Hỗ trợ build `.exe` nhẹ hơn bằng cách dùng `UPX` nén thủ công sau build
- Tối ưu code bằng cách sử dụng các hàm `try/except` để tránh lỗi

### ✅ Auto Login 3.4 (23/12/2024)

- Giao diện mới, hỗ trợ 2SGamerQQ
- Cho phép người dùng thêm hoặc bỏ 2SGamerQQ
- Thêm chỉnh tốc độ hack `+`, `.`
- Thêm chỉnh tốc độ hack `F9`, `F10`
- Thêm chỉnh tốc độ hack `DELETE`
- Ấn để tăng tốc độ hack `SPACE`

### ✅ Auto Login 3.3 (20/12/2024)

- Sửa tính năng đăng nhập (tăng tốc độ, bỏ qua update)
- Bảo mật tài khoản tốt hơn
- Thêm Update Shop và Nhiều Launcher
- Thêm tính năng bỏ qua update
- Thêm tính năng tăng tốc độ hack

### ✅ Auto Login 3.2 (01/12/2024)

- Sửa lỗi nhập UID khi chỉnh FPS

### ✅ Auto Login 3.1 (27/11/2024)

- Thêm Dark Mode và Hack Speed (ẩn)
- Cải thiện UI chọn tài khoản
- Thêm tính năng chọn tài khoản
- Thêm tính năng chọn FPS

### ✅ Auto Login 3.0

- Chọn launcher từ menu thay vì nhập tay
- Hỗ trợ nhiều tài khoản hơn 2
- Tùy chọn backup
- Tùy chọn chọn launcher
- Tùy chọn chọn tài khoản

### ✅ Auto Login 2.0

- Chọn thư mục game thay vì dán link
- Config tài khoản qua file TXT
- Chọn tài khoản từ danh sách

### ✅ Auto Login 1.0

- Giao diện cơ bản
- Nhập tay launcher, tài khoản
- Lưu cấu hình vào file
- Tự động đăng nhập

---

## 📌 Liên Hệ

- Trang chủ: [http://2sgamer.com](http://2sgamer.com)
- Facebook: [https://www.facebook.com/LeeQiFuong/](https://www.facebook.com/
- Phát triển bởi: **Yisu**  
- © 2024–2025 All Rights Reserved.
