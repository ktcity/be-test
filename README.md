# Fullstack Developer Test

Hoàn thành các task bên dưới theo để xây dựng một ứng dụng hoàn chỉnh.

## Một số yêu cầu

- Sử dụng NodeJs để code các API
  - Điểm cộng nếu dùng Expressjs hoặc NestJS để xây dựng ứng dụng ở Backend
  - Điểm cộng nếu dùng Prisma để connect tới Database
  - Điểm cộng nếu dùng NextJS kết hợp với Redux Saga để xây dựng ứng dụng ở Frontend
  - Điểm cộng nếu dùng Styled Components
- Viết hướng dẫn đê chạy ứng dụng
- Liệt kê các trang theo yêu cầu tương ứng và các API được call trong trang
- Ứng viên có thể sử dụng Database có sẵn gửi kèm theo email (Mysql) hoặc tự tạo database riêng, nếu dùng database riêng phải kèm theo cấu trúc và kiểu dữ liệu của mỗi trường (field)

## Task

#### Task 1: Xây dựng trang tạo user với các thông tin sau

- email: input email
- username: input text
- fullname: input text
- avatar: input file
- status: select box dropdown
- deleted: toogle box (boolean)

#### Task 2: Xây dựng trang quản lý user

- Mỗi trang sẽ có 5 user
- Có phân trang
- View list dưới dạng table
- Có lọc theo trạng thái

#### Task 3: Xây dựng trang cập nhật user

- Lấy thông tin user theo Id
- Cập nhật các thông tin có sẵn
- Hiển thị email nhưng không cho cập nhật

### Task nâng cao (Không bắt buộc, ứng viên sẽ note lại ứng task mình đã làm)

- Validate email
- Generate username từ fullname (fronten & backend nếu không tồn tại)
- Mỗi row trên table có Toogle box để cập nhật field "deleted"
- Thêm filter theo ngày tháng tạo user dựa trên "createdAt"
- Authentication dựa trên header với Token Bearer: Authorization: Bearer <token>
- Ngăn chặn các tấn công từ bên ngoài (ddos, xxs, sql injection, ...)

### Cấu trúc database

![database-structure](/images/database-structure.png "database-structure")
