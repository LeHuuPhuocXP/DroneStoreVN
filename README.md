# DroneShopVN — Flycam & Drone E-commerce Platform

**DroneShopVN** là nền tảng thương mại điện tử chuyên về flycam và drone, được xây dựng như đồ án môn Thực tập lập trình Web (Nhóm 7) và tiếp tục được phát triển, hoàn thiện sau khi kết thúc môn học.

Dự án mô phỏng một cửa hàng bán drone trực tuyến đầy đủ chức năng — từ trải nghiệm mua sắm của khách hàng đến hệ thống quản trị vận hành dành cho admin.

##  Tính năng nổi bật

### Dành cho khách hàng
-  Duyệt sản phẩm theo danh mục: Flycam mini, quay phim, thể thao/đua, nông nghiệp, du lịch, giám sát an ninh
-  Tìm kiếm, xem chi tiết sản phẩm, đánh giá & bình luận
-  Giỏ hàng, danh sách yêu thích (wishlist), lịch sử mua hàng
-  Đăng ký/đăng nhập thường và qua **Google OAuth**
-  Thanh toán trực tuyến qua **VNPay** (chuẩn bảo mật HMAC-SHA512)
-  Tích hợp vận chuyển **GHN** (Giao Hàng Nhanh) qua webhook
-  Blog, bài viết, khuyến mãi, chính sách bảo hành/thanh toán
-  Chat trực tiếp, gửi khiếu nại/hỗ trợ
-  Xem sản phẩm gần đây (Recently Viewed), thông báo qua SweetAlert2

### Dành cho quản trị viên (Admin)
-  Dashboard thống kê doanh thu, đơn hàng
-  Quản lý sản phẩm, danh mục, kho hàng (inventory), banner quảng cáo
-  Quản lý đơn hàng (đã xác nhận / chưa xác nhận / bị từ chối)
-  Quản lý khách hàng, đánh giá sản phẩm, khiếu nại
-  Quản lý chương trình khuyến mãi (kèm đồng hồ đếm ngược)
-  Quản lý blog/bài viết

##  Công nghệ sử dụng

| Thành phần | Công nghệ |
|---|---|
| Backend | Java (JSP/Servlet) |
| Server | Apache Tomcat 10 |
| Build tool | Gradle |
| Database | MySQL |
| Frontend | HTML, CSS, JavaScript, DataTables |
| Bảo mật | CSRF Protection, HMAC-SHA512 (VNPay) |
| Triển khai | Docker, Cloudflare Tunnel, Gradle SSH Plugin, MobaXterm |
| Xác thực | Google OAuth 2.0 |

##  License

Dự án phục vụ mục đích học tập và phát triển cá nhân.
