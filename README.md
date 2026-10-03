
# Smart Vehicle Challenge

Dự án phát triển hệ thống điều khiển cho xe thông minh (Smart Vehicle).

---

## 🛠 Môi trường khuyến nghị

Để dự án hoạt động ổn định và tối ưu nhất trong quá trình biên dịch, nạp code cũng như quản lý thư viện, **khuyến nghị sử dụng VS Code kết hợp với extension PlatformIO IDE** thay vì Arduino IDE thông thường.

### Tại sao nên dùng PlatformIO?

* Tự động quản lý thư viện và cấu hình board qua file `platformio.ini`.
* Tốc độ biên dịch (build) nhanh hơn.
* Hỗ trợ IntelliSense, tự động gợi ý code và gỡ lỗi (debug) chuẩn xác.

---

## 🚀 Hướng dẫn cài đặt và sử dụng

### 1. Chuẩn bị môi trường

1. Tải và cài đặt [Visual Studio Code](https://code.visualstudio.com/) (nếu chưa có).
2. Mở VS Code, vào mục **Extensions** (phím tắt `Ctrl + Shift + X`).
3. Tìm kiếm **PlatformIO IDE** và nhấn **Install**.
4. Chờ tiến trình cài đặt hoàn tất và khởi động lại VS Code nếu được yêu cầu.

### 2. Mở và chạy dự án

1. Clone hoặc tải source code dự án về máy:
```bash
git clone [https://github.com/ngphu2607/smart-vehicle-challenge.git](https://github.com/ngphu2607/smart-vehicle-challenge.git)

```


2. Mở VS Code -> chọn **File** -> **Open Folder...** -> chọn thư mục dự án vừa tải.
3. Chờ PlatformIO tự động tải các dependencies và thiết lập môi trường (thông báo hiển thị ở thanh trạng thái bên dưới).

### 3. Thao tác cơ bản với PlatformIO

Sử dụng các biểu tượng ở thanh trạng thái (dưới cùng của VS Code) hoặc thanh công cụ PlatformIO bên trái:

* **Build (Biên dịch):** Biểu tượng `✓` (Check mark) để kiểm tra lỗi cú pháp và biên dịch code.
* **Upload (Nạp code):** Biểu tượng `→` (Mũi tên sang phải) để nạp chương trình vào vi điều khiển (cần kết nối phần cứng qua cáp USB trước).
* **Serial Monitor:** Biểu tượng ổ cắm hoặc kính lúp để mở cổng Serial theo dõi log/dữ liệu truyền về máy tính.

---

## 📁 Cấu trúc thư mục cơ bản

* `src/`: Chứa mã nguồn chính của dự án (`main.cpp` / các module xử lý).
* `include/`: Chứa các file header (`.h`).
* `lib/`: Chứa các thư viện tự phát triển hoặc bên thứ ba dùng riêng cho dự án.
* `platformio.ini`: File cấu hình thông số chip, board, framework và tốc độ baud rate.

```

```
