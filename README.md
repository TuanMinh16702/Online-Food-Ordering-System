<h1 align="center"> Personal Project <br/>
 Đề tài: Online Food Ordering System
<h1>

# **I. Tổng quát**

<h2>Lí do:</h2>
<ul>
   <t>Trong bối cảnh phát triển mạnh mẽ của thương mại điện tử và công nghệ di động, việc đặt món ăn trực tuyến đã trở thành một xu hướng phổ biến trong đời sống hiện đại. Sự tiện lợi, nhanh chóng và linh hoạt của hình        thức đặt món ăn qua mạng không chỉ đáp ứng nhu cầu ẩm thực hằng ngày mà còn mở ra nhiều cơ hội kinh doanh mới trong lĩnh vực dịch vụ ăn uống. Thức ăn là một nhu cầu thiết yếu, phục vụ cho mọi đối tượng người dùng,       từ học sinh, sinh viên đến người đi làm và các hộ gia đình. Với nhịp sống bận rộn, người tiêu dùng ngày càng có xu hướng ưu tiên các dịch vụ giúp tiết kiệm thời gian và công sức. Một hệ thống chuyên cung cấp dịch        vụ đặt món ăn trực tuyến sẽ đáp ứng hiệu quả nhu cầu đó, đồng thời giúp các nhà hàng, quán ăn quản lý đơn hàng, khách hàng và thực đơn một cách khoa học và hiện đại.</t>
</ul>

# **II. Mô tả chức năng của từng đối tượng sử dụng**
<h2>Chủ cửa hàng:</h2>
<ul>
  <li>Đăng nhập</li>
  <li>Quản lý món ăn</li>
  <li>Quản lý khuyến mãi</li>
  <li>Quản lý đơn hàng</li>
  <li>Xem đánh giá</li>
  <li>Xem thống kê</li>
  <li>Tạo và chỉnh sửa tài khoản</li>
</ul>
<h3>Nhân viên:</h3>
<ul>
  <li>Đăng nhập</li>
  <li>Quản lý đơn hàng</li>
</ul>
<h3>Khách hàng:</h3>
<ul>
  <li>Đặt món</li>
  <li>Thanh toán</li>
  <li>Tìm kiếm</li>
  <li>Kiểm tra thông tin giỏ hàng</li>
  <li>Theo dõi đơn hàng</li>
  <li>Đánh giá đơn hàng</li>
</ul>

# **III. Yêu cầu chức năng**
Bộ phận: Chủ cửa hàng
| Công việc                  | Loại công việc             | Ghi chú                                                   |
|----------------------------|----------------------------|-----------------------------------------------------------|
| Đăng nhập                  | Tra cứu                    |                                                           |
| Quản lý nhân viên          | Lưu trữ                    |                                                           |
| Quản lý món ăn             | Lưu trữ                    | Chủ cửa hàng có thể chỉnh sửa, thêm và xóa món ăn         |
| Quản lý khuyến mãi         | Lưu trữ                    | Chủ cửa hàng có thể chỉnh sửa thêm và xóa khuyến mãi      |
| Quản lý đơn hàng           | Lưu trữ                    | Chủ cửa hàng có thể thay đổi các trạng thái của đơn hàng  |
| Xem trạng thái đơn hàng    | Tra cứu                    | Chủ cửa hàng có thể thêm hoặc khóa tài khoản của nhân viên|
| Xem thống kê doanh thu     | Tra cứu                    |                                                           | 


Bộ phận: Nhân viên
| Công việc                  | Loại công việc             | Ghi chú                                                   |
|----------------------------|----------------------------|-----------------------------------------------------------|
| Đăng nhập                  | Tra cứu                    |                                                           |
| Xem trạng thái đơn hàng    | Tra cứu                    | Xem tiến trình: đang xử lý, đang giao, hoàn tất           |
| Chỉnh sửa món ăn           | Lưu trữ                    | Thay đổi món ăn: hiển thị hết món, thay đổi mô tả món ăn  |
| Xem danh sách đơn hàng     | Tra cứu                    | Xem tổng các đơn hàng để tiến hành giao hàng              |
| Quản lý đơn hàng           | Lưu trữ                    | Cập nhật trạng thái đơn hàng                              |

Bộ phận: Khách hàng
| Công việc                         | Loại công việc              | Ghi chú                                            |
|-----------------------------------|-----------------------------|----------------------------------------------------|
| Quản lý giỏ hàng                  | Lưu trữ                     | Thêm, cập nhật, xóa sản phẩm trong giỏ             |
| Tra cứu sản phẩm                  | Tra cứu                     | Tìm kiếm theo tên, loại, giá…                      |
| Xem chi tiết thông tin sản phẩm   | Tra cứu                     | Hiển thị hình ảnh, mô tả, giá, khuyến mãi          |
| Thanh toán đơn hàng               | Xử lý nghiệp vụ             | Chọn phương thức thanh toán, xác nhận đơn          |
| Đánh giá sản phẩm                 | Lưu trữ                     | Người dùng có thể thêm/sửa đánh giá                |
| Theo dõi trạng thái đơn hàng      | Tra cứu                     | Xem tiến trình: đang xử lý, đang giao, hoàn tất    |

