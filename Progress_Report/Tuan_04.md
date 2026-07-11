# BÁO CÁO TIẾN ĐỘ TUẦN 4
  
**Trọng tâm:** Hiện thực hóa code chức năng quản trị (Phía Admin) và bổ sung tính năng cải tiến

## 1. Nội dung công việc
* Tích hợp đồng bộ mẫu giao diện quản trị SB Admin 2 vào cấu trúc Layout hệ thống phân hệ Admin.
* Viết toàn bộ mã nguồn chức năng CRUD (Thêm, Sửa, Xóa, Xem) cho các thực thể quản trị: Quản lý thông tin dịch vụ sửa chữa (PricingSettings), Quản lý phân loại danh mục, Quản lý trạng thái các đơn đặt lịch (Bookings), và phân hệ Quản lý phản hồi/đánh giá (Reviews).
* Thiết lập hệ thống giao diện Quản lý vai trò người dùng (Role Management) và ma trận phân quyền truy cập hệ thống.

## 2. Tài liệu liên quan
* Tài liệu API tích hợp hệ thống bảo mật tài khoản ASP.NET Identity.
* Giải pháp phân chia quyền hạn truy cập dựa trên vai trò Roles (phân tách rõ ranh giới giữa tài khoản Admin, Thợ sửa chữa và Khách hàng).

## 3. Khó khăn khi viết thêm chức năng
* Gặp trở ngại lớn khi tích hợp thêm các chức năng nâng cao theo đề xuất cải tiến từ hội đồng nghiên cứu:
  * Thiết lập tính năng thông báo nổi (Toast Notification) thời gian thực ngay khi có đơn đặt lịch sửa chữa nhà cửa mới đổ về hệ thống.
  * Gặp khó khăn khi viết logic gợi ý thông minh, tự động kiểm tra trùng khớp thông tin số điện thoại khách hàng cũ để đưa ra gợi ý liên kết hoặc tạo mới profile khách hàng nhanh tại trang Admin.
  * Việc thử nghiệm cấu hình truyền tải dữ liệu Realtime tiêu tốn rất nhiều thời gian cấu hình hệ thống và tối ưu mã nguồn.

## 4. Kết quả đạt được
* Hoàn thiện toàn vẹn tất cả các màn hình chức năng CRUD thuộc phân hệ quản trị của bộ phận Admin.
* Tích hợp thành công cơ chế phân quyền bảo mật cơ bản giúp ngăn chặn việc truy cập bất hợp pháp vào các URL hệ thống.
* Đồ án chạy tạm ổn
