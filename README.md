# **Phần 1. Phân tích:** Mô tả sơ đồ cây cấu trúc Heading cho file SRS.
PTIT-Learning
 1. Giới Thiệu ( heading 1 )
   1.2 Mục đích ( heading 2 )
   1.3 Phạm vi ( heaing 2 )
   1.4 Tài Liệu Hình Ảnh ( heading 2 )
 2. Mô tả tổng quan ( heading 1 )
   2.1 Tổng quan hệ thống ( heading 2 )
   2.2 Vai trò người dùng ( heading 2 )
 3. Mô tả chức năng lớp học ảo ( heading 1 )
   3.1 Tạo và quản lý lớp học ảo ( heading 2 )
   3.2 Tham gia lớp học ( heading 2 )
   3.3 Tính năng trong lớp học ( heading 2 )
   3.4 Ghi hình & lưu trữ ( heading 2 )
   3.5 chat & hỏi đáp ( heading 2 )
   3.6 chia sẻ tài liệu & bảng trắng ( heading 2 )
   3.7 Điểm danh & báo cáo tham gia ( heading 2 )
  4. Yêu cầu phi chức năng ( heading 1 )
   4.1 Hiệu năng ( heading 2 )
   4.2 Bảo mật ( heading 2 )
   4.3 Khả dụng ( heading 2 )
   4.4 Khả năng mở rộng ( heading 2 )
  5. Ràng buộc & giả định ( heading 1 )
  6. Phụ lục ( heading 1 )
# Phần 2. Triển Khai:File báo cáo hoàn chỉnh
   ## Word : đặc tả yêu cầu phần mềm (SRS ) Tính Năng : Lớp Học Ảo
### A. Cấu trúc  
   mã tài liệu : `SRS-VA-01` | Phiên bản 1.0 | Ngày : 20/05/2024
   mục tiêu : quản lý cấu trúc tài liệu bằng navigation pane thông qua tổ hợp phím ctrl + F --> chọn thẻ heading
### B. quy trình cập nhật cấu trúc
   1. nhấp chuột phải vào mục lục
   2. chọn `update field `
   3. chọn tùy chọn `update entire table` để cập nhật mục lục thêm heading 1, heading 2
   4. sau đó chọn ok và ctrl + S để hoàn thiện bài làm
  ## Excel - quản lý dữ liệu học viện
  ### A. ràng buộc database 
   - header duy nhất : STT , Họ và Tên , Email , SĐT , Nguồn Đăng Ký , Khóa Học Quan Tâm , Ngày Đăng Ký , Trạng Thái
   - không chừa các khoảng trống
  ### B. thao tác autofilter
  1. chọn một ô bất kỳ và nhấn tổ hợp phím crlt + shift + L để bật thanh công cụ autofilter.
  2. lọc khoa : click vào cột khoa và chọn khoa CNTT
  3. lọc điểm chuyên cần dưới 7
     - chọn cột điểm chuyên cần
     - chọn `number filters` sau đó chọn  `less than...`
     - chọn giá trị 7 và nhấn ok
   ## C. PowerPoing - Tổng Quan Nền Tảng ( Nền Tảng Học Trực Tuyến Dành Cho Mọi Người )
combo màu tối : 
    - background : nền navy đậm  
    - text : chữ trắng
    - accent cam : cho biểu đồ màu cam thêm nổi bật
# phần 3. Kiểm Thử: Nếu lọc sinh viên theo tên nhưng không ra kết quả ( dù nhìn thấy tên đó ), hãy trình bày cách dùng hàm TRIM để xử lý
 1. Nếu thực hiện lọc sinh viên ( ví dụ : Nguyễn Bảo Huy ) nhưng danh sách không trả về kết quả dù tên vẫn có
    - Nguyên nhân : chừa khoảng trống ở đầu chuỗi hoặc cuối chuỗi
 2. quy trình xử lý bằng hàm `TRIM`

    - dữ liệu thô dính khoảng trống -> tạo cột phụ và nhập công thức TRIM(B5) -> copy và paste special -> values đè lên cột gốc -> Bật tổ hợp phím Ctrl + Shift + L -> Thực hiện lọc lại thành công 
   
