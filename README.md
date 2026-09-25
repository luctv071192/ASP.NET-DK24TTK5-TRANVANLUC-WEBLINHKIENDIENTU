# ASP.NET-DK24TTK5-TRANVANLUC-WEBLINHKIENDIENTU

## ĐỒ ÁN: XÂY DỰNG WEBSITE BÁN LINH KIỆN ĐIỆN TỬ

###  THÔNG TIN SINH VIÊN
- **Họ và tên:** Trần Văn Lực
- **Email:** luctv071192@tvu-onschool.edu.vn
- **Lớp / Khóa:** DK24TTK5

### GIỚI THIỆU DỰ ÁN
Dự án **Website bán linh kiện điện tử** được xây dựng nhằm cung cấp giải pháp mua sắm các thiết bị, linh kiện điện tử trực tuyến một cách nhanh chóng, tiện lợi. Hệ thống hỗ trợ người dùng dễ dàng tìm kiếm, tham khảo thông số kỹ thuật và đặt hàng, đồng thời hỗ trợ quản trị viên quản lý kho hàng và đơn hàng một cách tối ưu.

---

###  MỤC TIÊU ĐỒ ÁN
- Xây dựng hoàn chỉnh một website bán hàng thương mại điện tử.
- Củng cố và áp dụng thực tế kiến thức về lập trình Web với **ASP.NET MVC** và quản trị cơ sở dữ liệu **SQL Server**.
- Thiết kế giao diện thân thiện.

###  CÔNG NGHỆ SỬ DỤNG
- **Backend:** ASP.NET MVC, C#
- **Frontend:** HTML5, CSS3, JavaScript, jQuery, Bootstrap
- **Database:** SQL Server
- **Công cụ phát triển:** Visual Studio, SQL Server Management Studio (SSMS), Git / GitHub

###  CHỨC NĂNG HỆ THỐNG

#### 1. Dành cho Khách hàng 
- **Trang chủ:** Hiển thị sản phẩm mới, sản phẩm nổi bật.
- **Danh mục & Sản phẩm:** Xem danh sách linh kiện theo từng loại 
- **Tìm kiếm & Lọc:** Tìm kiếm linh kiện theo tên, lọc sản phẩm theo mức giá hoặc danh mục.
- **Chi tiết sản phẩm:** Xem hình ảnh, mô tả chi tiết, giá bán và thông số kỹ thuật.
- **Giỏ hàng & Đặt hàng:** Thêm/sửa/xóa sản phẩm trong giỏ, tiến hành đặt hàng trực tuyến.
- **Quản lý tài khoản:** Đăng ký, đăng nhập, cập nhật thông tin cá nhân.

#### 2. Dành cho Quản trị viên 
- **Quản lý sản phẩm:** Thêm, sửa, xóa, cập nhật số lượng tồn kho linh kiện.
- **Quản lý danh mục:** Cập nhật các nhóm/loại linh kiện điện tử.
- **Quản lý đơn hàng:** Xem danh sách đơn hàng, duyệt đơn, cập nhật trạng thái giao hàng.
- **Quản lý người dùng:** Quản lý thông tin tài khoản khách hàng.

### HƯỚNG DẪN CÀI ĐẶT VÀ CHẠY DỰ ÁN

#### Bước 1: Clone dự án về máy
Mở **Git Bash** hoặc Terminal và chạy lệnh:
```bash
(https://github.com/luctv071192/ASP.NET-DK24TTK5-TRANVANLUC-WEBLINHKIENDIENTU.git)

#### Bước 2: Cấu hình Cơ sở dữ liệu (Database)
Mở phần mềm SQL Server Management Studio (SSMS).
Mở và chạy file kịch bản CSDL (file .sql) nằm trong thư mục database/ của dự án để khởi tạo Database.

#### Bước 3: Cấu hình Chuỗi kết nối (Connection String)
Mở solution dự án bằng Visual Studio.
Tìm đến file web.config ở thư mục gốc dự án.
Thay đổi thông tin Data Source (Server Name) trong đoạn connectionStrings cho phù hợp với SQL Server trên máy tính của bạn:
<connectionStrings>
  <add name="DefaultConnection" connectionString="Data Source=TEN_SERVER_CUA_BAN;Initial Catalog=TenDatabase;Integrated Security=True;" providerName="System.Data.SqlClient" />
</connectionStrings>

##### Bước 4: Chạy ứng dụng
Bấm phím F5 (hoặc nhấn nút Start / Run) trong Visual Studio để bắt đầu chạy chương trình trên trình duyệt.
