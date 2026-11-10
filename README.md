# BÁO CÁO THỰC HÀNH LẬP TRÌNH C# WINFORMS (BÀI 6.3, 6.4, 6.5 - 3-TIER ARCHITECTURE)

## MỤC 1: THÔNG TIN SINH VIÊN
* **Họ và tên sinh viên:** Phạm Gia Bảo
* **Mã sinh viên:** 24810320309
* **Lớp / Khóa:** D19QTANM1 (Lập trình .NET / C# WinForms)
* **Link Repository:** https://github.com/404-syntax/Bai_tap_6.3-6.4-6.5-_Pham_Gia_Bao_24810320309

---

## MỤC 2: HÌNH ẢNH KẾT QUẢ CÁC MÀN HÌNH CHỨC NĂNG

### 1. Bài 6.3: Hệ thống quản lý công việc và dự án
* **Màn hình Chính / Tổng quan:**
  ![Màn hình chính](Bài%20tập%206.3_Hệ%20thống%20quản%20lý%20công%20việc%20v.../docs/01_main_screen.png)
* **Màn hình Quản lý Danh mục (CRUD):**
  ![Màn hình CRUD](Bài%20tập%206.3_Hệ%20thống%20quản%20lý%20công%20việc%20v.../docs/02_crud_screen.png)
* **Màn hình Thực thi Nghiệp vụ chính:**
  ![Màn hình Nghiệp vụ](Bài%20tập%206.3_Hệ%20thống%20quản%20lý%20công%20việc%20v.../docs/03_transaction_screen.png)
* **Màn hình Báo cáo - Thống kê:**
  ![Màn hình Thống kê](Bài%20tập%206.3_Hệ%20thống%20quản%20lý%20công%20việc%20v.../docs/04_report_screen.png)
* **Minh họa An toàn Dữ liệu / Transaction Rollback:**
  ![Minh họa Xử lý lỗi](Bài%20tập%206.3_Hệ%20thống%20quản%20lý%20công%20việc%20v.../docs/05_error_handling.png)

---

### 2. Bài 6.4: Hệ thống quản lý Garage và bảo dưỡng xe
* **Màn hình Chính / Tổng quan:**
  ![Màn hình chính](Bài%20tập%206.4_Hệ%20thống%20quản%20lý%20Garage%20và%20.../docs/01_main_screen.png)
* **Màn hình Quản lý Danh mục (CRUD):**
  ![Màn hình CRUD](Bài%20tập%206.4_Hệ%20thống%20quản%20lý%20Garage%20và%20.../docs/02_crud_screen.png)
* **Màn hình Thực thi Nghiệp vụ chính:**
  ![Màn hình Nghiệp vụ](Bài%20tập%206.4_Hệ%20thống%20quản%20lý%20Garage%20và%20.../docs/03_transaction_screen.png)
* **Màn hình Báo cáo - Thống kê:**
  ![Màn hình Thống kê](Bài%20tập%206.4_Hệ%20thống%20quản%20lý%20Garage%20và%20.../docs/04_report_screen.png)
* **Minh họa An toàn Dữ liệu / Transaction Rollback:**
  ![Minh họa Xử lý lỗi](Bài%20tập%206.4_Hệ%20thống%20quản%20lý%20Garage%20và%20.../docs/05_error_handling.png)

---

### 3. Bài 6.5: Hệ thống quản lý đặt phòng và dịch vụ khách sạn
* **Màn hình Chính / Tổng quan:**
  ![Màn hình chính](Bài%20tập%206.5_Hệ%20thống%20quản%20lý%20đặt%20phòng%20.../docs/01_main_screen.png)
* **Màn hình Quản lý Danh mục (CRUD):**
  ![Màn hình CRUD](Bài%20tập%206.5_Hệ%20thống%20quản%20lý%20đặt%20phòng%20.../docs/02_crud_screen.png)
* **Màn hình Thực thi Nghiệp vụ chính:**
  ![Màn hình Nghiệp vụ](Bài%20tập%206.5_Hệ%20thống%20quản%20lý%20đặt%20phòng%20.../docs/03_transaction_screen.png)
* **Màn hình Báo cáo - Thống kê:**
  ![Màn hình Thống kê](Bài%20tập%206.5_Hệ%20thống%20quản%20lý%20đặt%20phòng%20.../docs/04_report_screen.png)
* **Minh họa An toàn Dữ liệu / Transaction Rollback:**
  ![Minh họa Xử lý lỗi](Bài%20tập%206.5_Hệ%20thống%20quản%20lý%20đặt%20phòng%20.../docs/05_error_handling.png)

---

## HƯỚNG DẪN CÀI ĐẶT & CHẠY DỰ ÁN
1. Mở SQL Server Management Studio (SSMS), thực thi file `Database/ScriptDB.sql` trong từng thư mục bài tập để khởi tạo CSDL và dữ liệu mẫu.
2. Mở file `.sln` bằng Visual Studio 2022.
3. Sửa lại chuỗi kết nối `ConnectionString` trong `App.config` hoặc lớp DAL.
4. Bấm **F5** để biên dịch và chạy chương trình.
