# Xây Dựng Website Bán Trà Sữa

## Thông Tin Nhóm Thực Hiện
- **110121251 – Kim Hoàng Nam**
- **117521003 – Nguyễn Hữu Luân**
- **117521001 – Phạm Quang Duy**
- **Lớp**: DA21TTC  
- **Khoa**: Kỹ Thuật và Công Nghệ  
- **Bộ Môn**: Công Nghệ Thông Tin  

---
## Mô Tả Dự Án
Website bán trà sữa được phát triển nhằm tạo ra một nền tảng thương mại điện tử, giúp doanh nghiệp tối ưu hóa quy trình kinh doanh và cung cấp trải nghiệm tốt nhất cho khách hàng. Website hỗ trợ:
- Hiển thị danh mục sản phẩm (trà sữa, đồ uống, v.v.).
- Quản lý giỏ hàng và đặt hàng.
- Quản lý nội dung như sản phẩm, bài viết, và khuyến mãi.
- Tích hợp giao diện quản trị thân thiện để quản lý đơn hàng, sản phẩm, và thống kê doanh thu.
  
---
  
## Nội Dung Công Việc

  - Tìm kiếm tài liệu.
  - Quản lý danh mục.
  - Phát triển giao diện cho trang sản phẩm và trang thanh toán.
  - Phân tích cơ sở dữ liệu
  - Tích hợp backend.
  - Quản lý sản phẩm
  - Trang giỏ hàng.
  - Quản lý khuyến mãi.
  - Kiểm thử hệ thống.
  - Viết báo cáo và slide thuyết trình.

---

## Kiến Trúc Hệ Thống
Hệ thống được xây dựng theo kiến trúc **MVC (Model-View-Controller)**:
- **Model**: Quản lý dữ liệu và logic nghiệp vụ. Model tương tác với cơ sở dữ liệu MySQL, bao gồm các bảng như:
  - `tbl_products`: Quản lý thông tin sản phẩm.
  - `tbl_users`: Quản lý thông tin người dùng.
  - `tbl_orders`: Quản lý đơn hàng.
  - `tbl_categories`: Quản lý danh mục sản phẩm.
  - `tbl_roles`: Quản lý vai trò người dùng.
  - `tbl_comments`: Lưu trữ đánh giá của khách hàng.
  - `tbl_promotions`: Quản lý các chương trình khuyến mãi.
  - `tbl_order_details`: Chi tiết đơn hàng.
- **View**: Hiển thị giao diện người dùng:
  - Trang chủ: Hiển thị sản phẩm nổi bật, danh mục và khuyến mãi.
  - Trang sản phẩm: Danh sách sản phẩm theo danh mục, tìm kiếm và lọc sản phẩm.
  - Trang chi tiết sản phẩm: Thông tin chi tiết về sản phẩm (hình ảnh, giá, mô tả, đánh giá).
  - Trang giỏ hàng: Quản lý sản phẩm trong giỏ, cập nhật số lượng, áp dụng mã giảm giá.
  - Trang thanh toán: Điền thông tin giao hàng, chọn phương thức thanh toán và xác nhận đơn hàng.
  - Trang đăng nhập/đăng ký: Giao diện cho người dùng tạo tài khoản hoặc đăng nhập.
  - Trang quản trị: Quản lý sản phẩm, đơn hàng, khuyến mãi, danh mục, và thống kê.
  - Trang thống kê: Hiển thị doanh thu, sản phẩm bán chạy, và các biểu đồ trực quan.
- **Controller**: Điều phối giữa Model và View. Các controller chính
  - `ProductController`: Xử lý các chức năng liên quan đến sản phẩm.
  - `CartController`: Quản lý giỏ hàng.
  - `OrderController`: Xử lý đặt hàng.
  - `AdminController`: Quản lý các chức năng dành cho quản trị viên.
  - `PromotionController`: Quản lý khuyến mãi.
  - `CommentController`: Xử lý đánh giá sản phẩm.

---

## Công Nghệ Sử Dụng
- **Database**: MySQL - Hệ quản trị cơ sở dữ liệu mạnh mẽ, phù hợp với ứng dụng thương mại điện tử.
- **Frontend**: 
  - HTML, CSS - Cấu trúc và tạo kiểu giao diện.
  - JavaScript - Tương tác động cho website.
  - Bootstrap - Tối ưu giao diện tương thích trên mọi thiết bị.
- **Backend**: 
  - PHP - Ngôn ngữ lập trình phía máy chủ phổ biến.
  - Laravel - Framework PHP mạnh mẽ, hỗ trợ phát triển nhanh và hiệu quả.
- **Môi Trường Phát Triển**: XAMPP - Phần mềm giả lập server.

