# Hệ thống Trắc nghiệm Trực tuyến (Exam Online)

Dự án được xây dựng nhằm tối ưu hóa quy trình quản lý ngân hàng câu hỏi, tổ chức kỳ thi và tự động hóa việc chấm điểm cho các cơ sở giáo dục. Hệ thống hỗ trợ đa người dùng với phân quyền chặt chẽ và giao diện trực quan.

## Tính năng cốt lõi

### 1. Quản trị hệ thống và phân quyền
* **Đăng nhập & Xác thực:** Phân quyền rõ ràng cho 3 đối tượng: **Admin, Giảng viên và Sinh viên**.
* **Quản lý tài khoản:** Quản trị viên có quyền tạo mới, cập nhật và phân quyền cho người dùng trong hệ thống.

### 2. Quản lý nội dung đào tạo (Giảng viên)
* **Ngân hàng câu hỏi:** Giảng viên dễ dàng thêm, sửa, xóa các câu hỏi trắc nghiệm.
* **Thiết lập đề thi:** Cho phép tạo đề thi, tùy chỉnh số lượng câu hỏi và thiết lập giới hạn thời gian làm bài.

### 3. Trải nghiệm người dùng (Sinh viên)
* **Làm bài trực tuyến:** Giao diện thi trực quan, có bộ đếm ngược thời gian thực.
* **Chám điểm tự động:** Hệ thống tự động tính toán kết quả và hiển thị điểm số ngay sau khi kỳ thi kết thúc.

### 4. Giao diện & Trải nghiệm
* Thiết kế đơn giản, tập trung vào tính tiện dụng.
* Phản hồi nhanh chóng, hoạt động ổn định trên các trình duyệt phổ biến.

## Công nghệ sử dụng
* **Backend:** PHP & Laravel Framework.
* **Database:** MySQL.
* **Frontend:** HTML5 & Blade Template, CSS3, JavaScript.

## Hướng dẫn chạy dự án
* **Clone dự án:** Mở `CMD` gõ lệnh `git clone https://github.com/KhoaNguyen-IT2K4/exam-online.git`.
* **Cài đăt thư viên:** `composer install`.
* **Cấu hình:** Copy file `.env.example` thành `.env`.
* **Khởi tạo:**
  * Chạy lệnh `php artisan key:generate` để tạo App Key.
  * Chạy lệnh `php artisan storage:link` để liên kết thư mục ảnh (nếu có).
* **Database:** Import file SQL tại thư mục `database/sql/exam_online.sql` vào MySQL.
* **Chạy:** gõ lệnh `php artisan serve` và truy cập `http://localhost:8000`.

## Tài khoản Demo
* **Quản trị viên:** `hung.nguyen@caothang.edu.vn` / `password`.
* **Giảng viên:** `kien.phan@caothang.edu.vn` / `password`.
* **Sinh viên:** `tuan.tran@caothang.edu.vn` / `password`.

*Dự án hoàn thành trong khuôn khổ đồ án tốt nghiệp*
