# qu-n-l-khoa-th-n-kinh-b-nh-vi-n-trung-ng
Họ và tên: vũ văn ngọc 

Mssv : k215480106061

Lớp K57KMT.01

BÀI TẬP 

#CHỨC NĂNG CƠ BẢN

# 1. QUẢN LÝ 

1.1. quản lý thông tin bệnh 

Thêm mới bệnh nhân

cập nhập thông tin bệnh nhân

xóa thông tin bệnh nhân

hiển thị danh sách bệnh nhân

1.2 .QUẢN LÝ THÔNG TIN BÁC 

thêm mới bác sĩ

cập nhập thông tin bác sĩ

xóa thông tin bác sĩ

hiển thị danh sách bác sĩ và số lần 

1.3. QUẢN LÝ LỊCH HẸN

thêm lịch hẹn mới 

cập nhập lịch hẹn

xóa lịch hẹn

hiện thị danh sách lịch hẹn của một bệnh nhân cụ thể

# 2.SỬ DỤNG TRIGGER VÀ PROCEDURE

2.1.trigger 

Cập nhật số lượng tồn kho của thuốc sau khi có cuộc hẹn mới

2.2.procedure

Tính tổng tiền cho đơn đặt hàng

# 3. TẠO VIEW

view để hiển thị thông tin lịch hẹn của bệnh nhân

View để thống kê số lần khám của từng bác sĩ

# 4.CHỨC NĂNG TRUY VẤN 

4.1 Hiển thị thông tin tất cả các bệnh nhân

4.2 Tìm kiếm thông tin bệnh nhân theo tên

# 5 truy vấn thông tin bác sĩ số lần khám

# 6. sử dụng trigger và procedure

6.1.Trigger để cập nhật số lượng tồn kho thuốc khi có lịch hẹn mới

6.2. Procedure để tính tổng tiền cho đơn đặt hàng

# 7.tạo các view

7.1.View để hiển thị thông tin lịch hẹn của bệnh nhân

7.2.View để thống kê số lần khám của từng bác sĩ

# 8.Quản lý tài nguyên và dịch vụ

8.1 Quản lý danh mục thuốc và vật tư y tế

Thêm mới và cập nhật thông tin thuốc:

Truy vấn danh sách thuốc theo các tiêu chí khác nhau

8.2 Quản lý các dịch vụ y tế bổ sung

Thêm mới và cập nhật thông tin dịch vụ y tế bổ sung

Truy vấn danh sách các dịch vụ y tế và chi phí 

# 9.Quản lý kết quả xét nghiệm và hồ sơ y tế điện tử

9.1.Quản lý kết quả xét nghiệm

Lưu trữ và quản lý kết quả xét nghiệm của bệnh nhân

Truy vấn kết quả xét nghiệm của một bệnh nhân cụ thể

9.2. Hồ sơ y tế điện tử

Lưu trữ hồ sơ y tế điện tử của bệnh nhân

Truy vấn hồ sơ y tế điện tử của bệnh nhân

# 10.Quản lý tài chính và thanh toán

10.1.Quản lý hóa đơn và thanh toán

Lưu trữ thông tin hóa đơn và thanh toán của bệnh nhân

Truy vấn các hóa đơn và thanh toán theo từng bệnh nhân

10.2.Thống kê doanh thu và chi phí

Thống kê tổng doanh thu từ các dịch vụ và thuốc

Thống kê chi phí theo từng khoản chi

# 11 Quản lý tài nguyên nhân lực và phân công công việc

11.1.Quản lý nhân sự bệnh viện

Thêm mới và cập nhật thông tin nhân viên

Truy vấn danh sách nhân viên theo từng phòng ban

11.2. Phân công công việc và lịch trực

Thêm mới và cập nhật thông tin lịch trực của nhân viên

Truy vấn lịch trực của nhân viên trong khoảng thời gian nhất định

# THIẾT KẾ CHƯƠNG TRÌNH TRONG SQL

# tạo các bảng
1. Bảng Patients (Bệnh nhân)
Khóa chính: PatientID



 
