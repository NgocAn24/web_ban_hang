I. Giới thiệu chung
Trang web bán đồ chơi được xây dựng bằng Laravel nhằm cung cấp một nền tảng mạnh mẽ giúp doanh nghiệp dễ dàng quản lý sản phẩm, khách hàng và đối tác. Hệ thống tập trung vào việc tối ưu hiệu suất, tính bảo mật và giao diện thân thiện với người dùng.

II
2.1. Frontend (Giao diện người dùng):

• HTML, CSS, JavaScript: Cung cấp giao diện cơ bản của website.

• Bootstrap: Được sử dụng để giúp giao diện website hiển thị đẹp trên nhiều
thiết bị (responsive).

• AJAX: Hỗ trợ gửi và nhận dữ liệu từ backend mà không cần phải tải lại
trang, cải thiện trải nghiệm người dùng.

2.2. Backend (Xử lý logic và dữ liệu):
• Laravel Framework: Là framework PHP mạnh mẽ hỗ trợ phát triển các
ứng dụng web, giúp xử lý yêu cầu từ người dùng, giao tiếp với cơ sở dữ liệu
và trả về dữ liệu.


                +------------------+
                |   Người Dùng     |
                +--------+---------+
                        |
                        v
                <!-- +-------------------+ -->
                |     Frontend      |
                | (HTML, CSS, JS)   |
                +--------+----------+
                        |
                        v
                +-------------------+
                |     Backend       |
                |  (Laravel, PHP)   |
                +--------+----------+
                        |
                        v
                +-------------------+
                |  MySQL Database   |
                +-------------------+

III. Sơ đồ kiến trúc hệ thống

1. Truy cập website: Người dùng truy cập vào website và duyệt các sản phẩm.
2. Tìm kiếm và thêm sản phẩm vào giỏ hàng: Người dùng có thể tìm kiếm sản
phẩm, xem chi tiết và thêm vào giỏ hàng.
3. Thanh toán: Khi người dùng thực hiện thanh toán, thông tin đơn hàng và giỏ
hàng được gửi đến backend để xử lý.
4. Cập nhật cơ sở dữ liệu: Backend xử lý đơn hàng, cập nhật thông tin vào cơ
sở dữ liệu MySQL.
5. Xác nhận và theo dõi đơn hàng: Hệ thống hiển thị trạng thái đơn hàng và
gửi thông tin xác nhận đến người dùng (qua email hoặc giao diện web).
