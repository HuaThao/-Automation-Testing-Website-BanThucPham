
# Ứng dụng Selenium WebDriver để kiểm thử website bán thực phẩm

## 📌 Giới thiệu

Đây là báo cáo thực tập tốt nghiệp với đề tài **"Ứng dụng Selenium WebDriver để kiểm thử website bán thực phẩm"**. Dự án nhằm xây dựng và thực hiện các ca kiểm thử tự động giúp đảm bảo chất lượng phần mềm, giảm thời gian và công sức kiểm thử thủ công.

## 🛠️ Công nghệ sử dụng

- **Ngôn ngữ lập trình:** Java
- **Công cụ kiểm thử:** Selenium WebDriver
- **Trình quản lý dự án:** Maven
- **Môi trường phát triển:** Eclipse IDE
- **Công cụ báo cáo:** Allure Report
- **Trình duyệt hỗ trợ:** Microsoft Edge (qua EdgeDriver)
- **Máy chủ web:** XAMPP (Apache, MySQL)

## 📋 Mục tiêu

- Tự động hóa các quy trình kiểm thử chức năng chính của website bán thực phẩm.
- Kiểm thử khả năng hiển thị dữ liệu giữa người dùng và quản trị viên.
- Đảm bảo các quy trình trong các trang: thêm vào giỏ hàng, giỏ hàng, thông tin nhận hàng và đơn hàng được hoạt động ổn định.

## 🔧 Cài đặt website bán thực phẩm (PHP + XAMPP)

1. **Cài đặt XAMPP**:
   - Tải và cài đặt XAMPP từ [https://www.apachefriends.org/](https://www.apachefriends.org/).
   - Mở XAMPP Control Panel và khởi động **Apache** và **MySQL**.

2. **Cài đặt cơ sở dữ liệu**:
   - Mở trình duyệt truy cập `http://localhost/phpmyadmin`.
   - Tạo cơ sở dữ liệu mới, ví dụ: `banthucpham`.
   - Import file SQL từ thư mục `banthucpham.sql` trong dự án.

3. **Chạy website**:
   - Đặt mã nguồn web vào thư mục `htdocs`, ví dụ: `C:\xampp\htdocs\BanThucPham`.
   - Truy cập website tại: `http://localhost/BanThucPham`.

4. **Cấu hình file kiểm thử (nếu cần)**:
   - Đảm bảo các file test Selenium sử dụng đúng URL của web như `http://localhost/BanThucPham`.


## ✅ Các trang được kiểm thử:

- Thêm sản phẩm vào giỏ hàng
- Giỏ hàng
- Thông tin nhận hàng
- Đơn hàng

## 🧪 Cách chạy kiểm thử

1. **Clone dự án:**

   ```bash
   git clone https://github.com/HuaThao/-Automation-Testing-Website-BanThucPham.git
   ```

2. **Cài đặt dependencies với Maven:**

   ```bash
   mvn clean install
   ```

3. **Chạy test:**

   ```bash
   mvn test
   ```

4. **Xem báo cáo Allure (nếu có cấu hình):**

   ```bash
   allure serve target/allure-results
   ```

## 📁 Cấu trúc thư mục

```
├── src
│   ├── main
│   │   └── java
│   └── test
│       └── java
│           └── tests
├── pom.xml
├── README.md
└── ...
```

## 📖 Tài liệu đi kèm

- Báo cáo thực tập tốt nghiệp (file PDF)
- Bộ test case thủ công
- Mô tả môi trường kiểm thử và kết quả kiểm thử

## 👤 Tác giả

- Họ và tên: Hứa Văn Thảo
- MSSV: 3120221461
- Trường: Trường Đại học Sư phạm Đà Nẵng
- Email: 3120221461@ued.udn.vn

---
