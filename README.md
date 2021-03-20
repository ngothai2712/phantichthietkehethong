# Đề tài: Xây dựng hệ thống sắp xếp công việc theo ca cho nhân viên

## I. Giới thiệu
Hệ thống sắp xếp lịch làm việc cho nhân sự của quán cà phê A. Hệ thống sẽ gợi ý và đưa ra gợi ý sắp xếp công việc theo ca dựa trên thông tin đăng ký lịch làm việc của nhân viên theo tuần. Dựa trên gợi ý này, quản lý có thể tuỳ chỉnh và đưa ra bảng thời gian biểu cả tuần cho nhân viên

### Bài toán mô phỏng hệ thống: 
Trong một quán cà phê có tổng cộng tất cả 6 nhân viên và 2 bạn quản lý. Mỗi một ngày có 3 ca làm việc: Sáng, chiều và tối. Quán không nghỉ ngày nào trong tuần.
Biết rằng, mỗi một bạn nhân viên phải đăng ký tối thiểu 3 buổi làm việc/tuần, mỗi ca thì cần 2-3 bạn nhân viên và ca nào cũng phải có 1 quản lý. Nhân viên không được phép làm quá 2 ca/ngày. Trong trường hợp có một ca không có nhân viên hoặc quản lý nào chọn thì hệ thống sẽ tự chỉ định theo lượng đăng ký.
1. Tạo form đăng ký lịch làm việc cho các bạn nhân viên và quản lý theo tuần. Hãy sắp xếp lịch sao cho cân đối nhất có thể.
2. Trong một ca cần có ít nhất một bạn làm phục vụ bàn, hãy sắp xếp lịch để cho tất cả 6 bạn nhân viên đều phải làm phục vụ với số lượng ca cân bằng nhất có thể.
3. Ca chiều thường là ca có lượng khách đông nhất, ca có lượng khách ít nhất là ca sáng, hãy tìm cách phân bố lịch để đáp ứng được với công việc.
4. Một bạn nhân viên báo ốm trong tuần, hãy sắp xếp lịch trực ca để không ảnh hưởng đến công việc.

## II. Thông tin chung về hệ thống
### Chức năng chung:
1. Quản lý thông tin của nhân viên: Thêm, sửa, xóa.
2. Đăng nhập và đăng ký tài khoản nhân viên
3. Nhận đăng ký ca làm việc
4. Tự động đề xuất sắp xếp lịch làm việc dựa trên đăng ký của nhân viên.
5. Tính lương dựa theo ca
6. Nhân viên có thể kiểm tra lịch làm việc của bản thân và của những nhân viên khác.
7. Chức năng đổi ca giữa nhân viên.
8. Hệ thống báo nghỉ ốm dành cho nhân viên gửi đến quản lý
### Mục tiêu
Đề tài chú trọng đến việc quản lý và sắp xếp lịch làm việc của nhân viên theo một cách hiệu quả và công bằng nhất về mặt số lượng ca làm việc cho các bạn nhân viên.
Đối tượng tác động bao gồm nhân viên và quản lý
### Thu thập dữ liệu
Dữ liệu đầu vào của hệ thống là bảng danh sách đăng ký lịch làm việc của các bạn nhân viên
### Công nghệ sử dụng
Chương trình được cài đặt trên nền web sử dụng
- Ngôn ngữ lập trình: Java, JavaScript
- Framework phát triển ứng dụng: Spring Boot (Java), ReactJS (JavaScript).
