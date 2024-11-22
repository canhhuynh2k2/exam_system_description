# exam_system_description
## 1) Giới thiệu chức năng
- Quản lý người dùng:  
  • Cho phép các thành viên đăng nhập và quản lý thông tin cá nhân.  
  • Cho phép quản trị viên quản lý tài khoản và quyền người dùng  
  • Cho phép giảng viên quản lý danh sách sinh viên làm bài thi  
  • Cho phép tất cả người dùng được phép khôi phục mật khẩu bằng gmail đã đăng ký • Xác thực người dùng để đảm bảo tính bảo mật và truy cập hợp lệ.  
- Quản lý ngân hàng câu hỏi:  
  • Cho phép giảng viên thêm, sửa, xóa các ngân hàng câu hỏi  
  • Cho phép giảng viên quản lý danh mục ngân hàng câu hỏi  
  • Cho phép phân loại câu hỏi theo phần, theo mức độ khó  
  • Cho phép giảng viên thêm, sửa, xóa câu hỏi và đáp án trắc nghiệm  
  • Cho phép giảng viên thêm câu hỏi bằng import file excel  
- Quản lý bài thi:  
  • Cho phép giảng viên tạo bài thi  
  • Cho phép giảng viên quản lý cấu hình bài thi: thời gian bắt đầu, thời gian kết thúc,  random câu hỏi, random câu trả lời, số câu hỏi trong các phần của bộ đề thi. • Cho phép giảng viên quản lý danh sách sinh viên tham gia.  
  - Thi trực tuyến:  
  • Hiển thị câu hỏi và thu thập câu trả lời từ sinh viên.  
  • Tính toán điểm số tự động dựa trên câu trả lời của sinh viên.  
- Báo cáo và thống kê:  
  • Báo cáo kết quả thi theo sinh viên: Cho phép giảng viên xem báo cáo kết quả thi theo  sinh viên: hiển thị điểm số, số câu trả lời đúng/sai, thời gian hoàn thành, và các thống  kê khác cho sinh viên sau khi hoàn thành một bài kiểm tra.
  • Báo cáo thống kê tổng quan bài thi: Cho phép giảng viên xem báo cáo kết quả thi theo  bài thi gồm tổng hợp kết quả thi của tất cả sinh viên tham gia một bài kiểm tra cụ thể bao gồm tổng số sinh viên, điểm số trung bình, phổ điểm, thời gian hoàn thành trung  bình.
 
--------------------------
## 2) Công nghệ sử dụng
- Frontend: ReactJS/NextJS, Material UI
- Backend: Spring Boot, Spring Cloud, Spring Data, Spring Security, Service discovery, Restful API, gRPC
- Message Queue: RabbitMQ
- Database: Postgresql, MongoDB, Redis
- Deploy: Docker
--------------------------
## 3) Kiến trúc tổng quan
![image](https://github.com/user-attachments/assets/9572455a-0702-4ade-893c-c522cea791be)

## 4) Thành phần hệ thống
--------------------------
