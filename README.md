# BÁO CÁO THỰC HÀNH LẬP TRÌNH C# WINFORMS (BÀI 6.3, 6.4, 6.5 - 3-TIER ARCHITECTURE)

## MỤC 1: THÔNG TIN SINH VIÊN
* **Họ và tên sinh viên:** Phạm Gia Bảo
* **Mã sinh viên:** 24810320309
* **Lớp / Khóa:** D19QTANM1 (Lập trình .NET / C# WinForms)
* **Link Repository:** https://github.com/404-syntax/Bai_tap_6.3-6.4-6.5-_Pham_Gia_Bao_24810320309

---

## MỤC 2: HÌNH ẢNH KẾT QUẢ CÁC MÀN HÌNH CHỨC NĂNG

### 1. Bài 6.3: Hệ thống quản lý công việc và tiến độ dự án
* **Màn hình Chính / Kanban View:**
  ![Giao diện KanbanView](images/giao%20di%E1%BB%87n%20KanbanList%20View.png)
* **Quản lý dự án và công việc:**
  ![Quản lý dự án](images/Qu%E1%BA%A3n%20l%C3%BD%20d%E1%BB%B1%20%C3%A1n%20v%C3%A0%20c%C3%B4ng%20vi%E1%BB%87c.png)
* **Phân công và cập nhật trạng thái:**
  ![Phân công công việc](images/Ph%C3%A2n%20c%C3%B4ng%20v%C3%A0%20c%E1%BA%ADp%20nh%E1%BA%ADt%20tr%E1%BA%A1ng%20th%C3%A1i%20c%C3%B4ng%20vi%E1%BB%87c.png)
* **Cảnh báo công việc quá hạn & Xử lý dữ liệu:**
  ![Cảnh báo quá hạn](images/C%E1%BA%A3nh%20b%C3%A1o%20c%C3%B4ng%20vi%E1%BB%87c%20qu%C3%A1%20h%E1%BA%A1n%20v%C3%A0%20x%E1%BB%AD%20l%C3%BD%20d%E1%BB%AF%20li%E1%BB%87u.png)
* **Báo cáo tiến độ và tỷ lệ hoàn thành:**
  ![Báo cáo tiến độ](images/B%C3%A1o%20c%C3%A1o%20ti%E1%BA%BFn%20%C4%91%E1%BB%99%20v%C3%A0%20t%E1%BB%B7%20l%E1%BB%87%20ho%C3%A0n%20th%C3%A0nh.png)

---

### 2. Bài 6.4: Hệ thống quản lý Garage và bảo dưỡng xe ô tô
* **Màn hình chính hệ thống Garage:**
  ![Màn hình chính Garage](images/M%C3%A0n%20h%C3%ACnh%20ch%C3%ADnh%20c%E1%BB%A7a%20h%E1%BB%87%20th%E1%BB%91ng%20Garage.png)
* **Quản lý khách hàng, xe và phụ tùng:**
  ![Quản lý khách hàng xe phụ tùng](images/Qu%E1%BA%A3n%20l%C3%BD%20kh%C3%A1ch%20h%C3%A0ng%2C%20xe%20v%C3%A0%20ph%E1%BB%A5%20t%C3%B9ng.png)
* **Lập phiếu sửa chữa và thay thế phụ tùng:**
  ![Lập phiếu sửa chữa](images/L%E1%BA%ADp%20phi%E1%BA%BFu%20s%E1%BB%ADa%20ch%C6%B0%E1%BB%9Dis%20v%C3%A0%20thay%20th%E1%BA%BF%20ph%E1%BB%A5%20t%C3%B9ng.png)
* **Kiểm tra tồn kho & Transaction Rollback:**
  ![Transaction Rollback](images/Ki%E1%BB%83m%20tra%20t%E1%BB%93n%20kho%20v%C3%A0%20x%E1%BB%AD%20l%C3%BD%20Transaction%20Rollback.png)
* **Thanh toán và thống kê chi phí sửa chữa:**
  ![Thanh toán thống kê](images/Thanh%20to%C3%A1n%20v%C3%A0%20th%E1%BB%91ng%20k%C3%AA%20chi%20ph%C3%AD%20s%E1%BB%ADa%20ch%C6%B0%E1%BB%9Da.png)

---

### 3. Bài 6.5: Hệ thống quản lý đặt phòng và dịch vụ Karaoke
* **Màn hình chính hệ thống:**
  ![Màn hình chính Karaoke](images/M%C3%A0n%20h%C3%ACnh%20ch%C3%ADnh.png)
* **Sơ đồ phòng hát trực quan:**
  ![Sơ đồ phòng hát](images/S%C6%A1%20%C4%91%E1%BB%93%20ph%C3%B2ng%20h%C3%A1t%20tr%E1%BB%B1c%20quan.png)
* **Quản lý phòng hát và danh mục dịch vụ:**
  ![Quản lý phòng dịch vụ](images/Qu%E1%BA%A3n%20l%C3%BD%20ph%C3%B2ng%20h%C3%A1t%20v%C3%A0%20danh%20m%E1%BB%A5c%20d%E1%BB%8Bch%20v%E1%BB%A5.png)
* **Mở phòng, gọi dịch vụ và thanh toán:**
  ![Mở phòng gọi dịch vụ 1](images/M%E1%BB%9F%20ph%C3%B2ng%2C%20g%E1%BB%8Di%20d%E1%BB%8Bch%20v%E1%BB%A5%20v%C3%A0%20thanh%20to%C3%A1n.png)
  ![Mở phòng gọi dịch vụ 2](images/M%E1%BB%9F%20ph%C3%B2ng%2C%20g%E1%BB%8Di%20d%E1%BB%8Bch%20v%E1%BB%A5%20v%C3%A0%20thanh%20to%C3%A1n1.png)
  ![Mở phòng gọi dịch vụ 3](images/M%E1%BB%9F%20ph%C3%B2ng%2C%20g%E1%BB%8Di%20d%E1%BB%8Bch%20v%E1%BB%A5%20v%C3%A0%20thanh%20to%C3%A1n2.png)

---

## HƯỚNG DẪN CÀI ĐẶT & CHẠY DỰ ÁN
1. Mở SQL Server Management Studio (SSMS), thực thi file `Database/ScriptDB.sql` trong từng thư mục bài tập để khởi tạo CSDL và dữ liệu mẫu.
2. Mở file `.sln` bằng Visual Studio 2022.
3. Sửa lại chuỗi kết nối `ConnectionString` trong `App.config` hoặc lớp DAL.
4. Bấm **F5** để biên dịch và chạy chương trình.
