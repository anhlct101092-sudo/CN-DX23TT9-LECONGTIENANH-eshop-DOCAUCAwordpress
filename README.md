# CN-DX23TT9-LECONGTIENANH-eshop-DOCAUCAwordpress
# Đồ án: Website Bán Dụng Cụ và Phụ Kiện Câu Cá
**Sinh viên thực hiện:** LÊ CÔNG TIẾN ANH
**Giảng viên hướng dẫn:** ThS. Nguyễn Hoàng Duy Thiện

## 1. Tóm tắt dự án
Xây dựng website bán dụng cụ và phụ kiện câu cá bằng WordPress và WooCommerce giúp duyệt sản phẩm, đặt hàng và quản lý đơn hàng.

## 2. Hướng dẫn cài đặt (Setup)
1. Cài đặt XAMPP (PHP, MySQL).
2. Cài đặt XAMPP:

Tải XAMPP bản dành cho Windows tại trang chủ apachefriends.org.
Mở file vừa tải để cài đặt (cứ nhấn Next liên tục đến khi hoàn tất).
Khởi động hệ thống:
Mở phần mềm XAMPP Control Panel lên.
Nhấn nút Start ở dòng Apache và MySQL. (Chờ hai dòng này sáng màu xanh lá là thành công).
Tạo Database:
Mở trình duyệt web, gõ địa chỉ: localhost/phpmyadmin/.
Nhấn vào tab Cơ sở dữ liệu (Databases).
Ô "Tên cơ sở dữ liệu", gõ: docau_db.
Ô bên cạnh chọn utf8mb4_unicode_ci rồi nhấn Tạo (Create).

3. Tải và cấu hình lõi WordPress.
Chuẩn bị mã nguồn:
Vào wordpress.org/download/, tải file .zip mới nhất về.
Giải nén file đó ra, bạn sẽ được một thư mục tên là wordpress.
Chép thư mục wordpress này vào đường dẫn C:\xampp\htdocs\.
Đổi tên thư mục wordpress thành docau.

Khai báo Website:
Mở trình duyệt, gõ địa chỉ: localhost/docau.
Chọn ngôn ngữ Tiếng Việt -> Nhấn Tiếp tục -> Nhấn Thực hiện ngay.
Tên Database: gõ docau_db.
Tên người dùng: gõ root.
Mật khẩu: (Xóa trắng, không gõ gì vào đây).
Nhấn Gửi -> Bắt đầu cài đặt.

Tạo tài khoản Quản trị Admin:
Điền Tên website (VD: Thế Giới Đồ Câu).
Tự tạo một Tên đăng nhập và Mật khẩu (Nhớ kỹ để sau này đăng nhập quản lý web). Nhấn Cài đặt WordPress.

Cài plugin Bán hàng (WooCommerce):
Đăng nhập vào quản trị web bằng tài khoản vừa tạo.
Nhìn menu bên trái, chọn Plugin -> Cài mới.
Gõ WooCommerce vào ô tìm kiếm. Nhấn Cài đặt ngay rồi nhấn Kích hoạt.

3. Import file cơ sở dữ liệu từ thư mục `setup/docau_db.sql` vào phpMyAdmin.
4. Chép mã nguồn giao diện vào thư mục `wp-content/themes/` và kích hoạt.
