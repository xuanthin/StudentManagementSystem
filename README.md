# Quản lý sinh viên

Đây là Hệ thống quản lý sinh viên dựa trên bảng điều khiển, là một ứng dụng đơn giản được thiết kế để quản lý hồ sơ sinh viên, bao gồm tạo, cập nhật và xóa thông tin sinh viên. Ngoài ra, nó cho phép phân công các khóa học cho sinh viên, chèn điểm của sinh viên, tính điểm trung bình và xem các khóa học và khoa có sẵn.

# Các chức năng chính của Hệ thống quản lý sinh viên này bao gồm:

1. **Tạo Sinh viên**: Người dùng có thể nhập ID, họ, tên, ngày sinh và ID khoa của sinh viên để tạo hồ sơ sinh viên mới trong cơ sở dữ liệu.

2. **Hiển thị Sinh viên**: Hàm này truy xuất và hiển thị danh sách tất cả sinh viên được lưu trữ trong cơ sở dữ liệu, bao gồm thông tin cơ bản của họ như tên, ngày sinh và ID khoa.

3. **Cập nhật sinh viên**: Người dùng có thể cập nhật thông tin của một sinh viên hiện tại bằng cách cung cấp ID của họ và sửa đổi tên, họ, ngày sinh và ID khoa.

4. **Xóa sinh viên**: Cho phép xóa hồ sơ sinh viên bằng cách chỉ định ID của sinh viên.

5. **Thêm khóa học cho sinh viên**: Tính năng này cho phép người dùng chỉ định các khóa học cho sinh viên bằng cách chọn ID sinh viên và ID khóa học từ danh sách các khóa học có sẵn.

6. **Chèn điểm và tính điểm trung bình**: Người dùng có thể nhập điểm cho sinh viên trong một khóa học cụ thể và hệ thống sẽ tự động tính điểm trung bình dựa trên điểm được cung cấp.

7. **Tìm kiếm sinh viên**: Chức năng này cho phép người dùng tìm kiếm một sinh viên cụ thể theo ID của họ và hiển thị thông tin chi tiết về sinh viên đó, bao gồm các khóa học họ đăng ký và điểm tương ứng của họ.

8. **Xem các khóa học và khoa**: Người dùng có thể xem danh sách các khóa học và khoa có sẵn, đồng thời họ cũng có thể chèn các khóa học và khoa mới.

# Công nghệ:

- C#
- .NET SDK (8.0.x)
- Microsoft SQL Server (SQL Express 2022)

