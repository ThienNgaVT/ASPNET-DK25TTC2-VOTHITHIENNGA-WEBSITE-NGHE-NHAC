# Tuan_4.md
# 📑 BÁO CÁO TIẾN ĐỘ ĐỒ ÁN - TUẦN 4
* **ĐẠI HỌC TRÀ VINH**
* **Trường:** Kỹ thuật và Công nghệ 
* **Bộ môn:** Công nghệ Thông tin 
* **Đề tài:** Xây dựng website Nghe nhạc trực tuyến trên nền tảng ASP.NET 
***Sinh viên thực hiện:** Võ Thị Thiên Nga 
* **Mã số sinh viên:** 170125155
* **Thời gian báo cáo:** 13/07/2026 - 19/07/2026
---

## 1. Nội dung công việc
* Nhúng và tích hợp đồng bộ các thư viện Bootstrap, Font-Awesome, Datatable vào phân hệ quản trị của người quản lý.
* Hiện thực hóa mã nguồn các chức năng CRUD (Thêm, Sửa, Xóa, Xem) cho các thực thể dữ liệu cốt lõi thuộc quyền quản trị của Admin.
* Viết code chức năng hiển thị danh sách bài hát (`DSBaiHat`), thêm mới một bài hát kèm theo upload file nhạc, file hình ảnh lên server, và chỉnh sửa thông tin bài hát.
* Viết code chức năng hiển thị danh sách tài khoản (`DSTaiKhoan`), khởi tạo người dùng mới từ trang quản trị và cập nhật chỉnh sửa thông tin hồ sơ tài khoản.
* Xây dựng các màn hình giao diện quản lý chi tiết: thêm mới và chỉnh sửa thông tin Ca sĩ, Thể loại nhạc, và Chủ đề âm nhạc.
* Thiết lập bộ lọc kiểm tra vai trò dựa trên thuộc tính `Role` trong bảng `account` để phân quyền hiển thị giao diện Admin một cách nghiêm ngặt.

## 2. Tài liệu liên quan
* Tài liệu kỹ thuật phân quyền hệ thống và thiết lập điều hướng bảo mật website.
* Thư viện xử lý tập tin `HttpPostedFileBase` phục vụ logic upload và lưu trữ tài nguyên đa phương tiện (`/Sound`, `/image`).

## 3. Khó khăn gặp phải
* Gặp trở ngại lớn khi viết mã xử lý các ràng buộc khi thực hiện xóa dữ liệu (ví dụ: không cho phép xóa ca sĩ hoặc thể loại khi đang có bài hát liên kết thuộc khóa ngoại đó).
* Khả năng và thời gian thực hiện còn hạn chế, dẫn đến một số ý tưởng nâng cao về phân quyền đa cấp, kết bạn và tương tác chia sẻ playlist thời gian thực giữa các tài khoản chưa thể thực thi hoặc chưa hoạt động thực sự ổn định.

## 4. Kết quả đạt được
* Hoàn thiện toàn bộ các tính năng quản trị CRUD cho danh sách bài hát, tài khoản người dùng, ca sĩ, thể loại và chủ đề.
* Tích hợp thành công cơ chế phân quyền bảo mật cơ bản, bảo vệ an toàn luồng dữ liệu quản trị hệ thống.
