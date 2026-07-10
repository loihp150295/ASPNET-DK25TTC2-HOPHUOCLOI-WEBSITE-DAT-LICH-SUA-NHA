# BÁO CÁO TIẾN ĐỘ TUẦN 3
**Thời gian:** 06/07/2026 - 12/07/2026  
**Trọng tâm:** Hiện thực hóa code chức năng cốt lõi (Phía Khách hàng)

## 1. Nội dung công việc
* Thực hiện cấu hình chuỗi kết nối (Connection String) đến SQL Server trong file cấu hình hệ thống Web.config.
* Tiến hành xây dựng mã nguồn (code) cho phân hệ phía Khách hàng: Màn hình trang chủ hiển thị dịch vụ, danh sách các loại hình sửa chữa, phân loại và bộ lọc theo Hãng cung cấp hoặc Nhu cầu sửa chữa đặc thù (điện, nước, chống thấm, sơn sửa).
* Hiện thực hóa logic nghiệp vụ Giỏ hàng dịch vụ (thêm dịch vụ, sửa đổi số lượng thợ/khối lượng trực tiếp, và xóa lịch hẹn).
* Xây dựng luồng xử lý Đặt lịch sửa chữa trực tuyến và giao diện cho phép khách hàng tra cứu, xem lại lịch sử đặt lịch mua dịch vụ.

## 2. Tài liệu liên quan
* Tài liệu hướng dẫn kỹ thuật điều hướng ASP.NET Routing và cơ chế xử lý ActionResults của Controller.
* Cơ chế quản lý dữ liệu Session trong ASP.NET nhằm mục đích lưu trữ thông tin giỏ hàng dịch vụ tạm thời cho khách truy cập.

## 3. Khó khăn gặp phải
* Gặp khó khăn khi xử lý bài toán đồng bộ dữ liệu giỏ hàng đặt lịch: khi người dùng thay đổi số lượng, khối lượng dịch vụ trực tiếp tại giao diện front-end, hệ thống cần tính toán lại tổng chi phí tạm tính ngay lập tức mà không làm tải lại toàn bộ trang (Page Reload).
* Cần nghiên cứu chuyên sâu để áp dụng thành thạo giải pháp bất đồng bộ kết hợp AJAX và jQuery.

## 4. Kết quả đạt được
* Hệ thống vận hành ổn định luồng đặt lịch dịch vụ khép kín từ khâu chọn loại hình sửa chữa nhà cửa đến lúc lưu đơn đặt lịch (Booking) thành công vào cơ sở dữ liệu.
