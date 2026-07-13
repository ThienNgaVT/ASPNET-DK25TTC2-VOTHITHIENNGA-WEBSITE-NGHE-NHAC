# Tuan_3.md
# 📑 BÁO CÁO TIẾN ĐỘ ĐỒ ÁN - TUẦN 3
* **ĐẠI HỌC TRÀ VINH**
* **Trường:** Kỹ thuật và Công nghệ 
* **Bộ môn:** Công nghệ Thông tin 
* **Đề tài:** Xây dựng website Nghe nhạc trực tuyến trên nền tảng ASP.NET 
* **Sinh viên thực hiện:** Võ Thị Thiên Nga 
* **Mã số sinh viên:** 170125155 
* **Thời gian báo cáo:** 06/07/2026 - 12/07/2026

---

## 1. Nội dung công việc
* Thiết lập cấu hình chuỗi kết nối cơ sở dữ liệu (Connection String) kết nối ứng dụng với Microsoft SQL Server, ứng dụng công nghệ LINQ để thực hiện truy vấn và tương tác dữ liệu nhanh chóng.
* Hiện thực hóa mã nguồn chức năng đăng ký (`SignUp`) và đăng nhập (`Login`) phía người dùng hệ thống.
* Xây dựng giao diện trang chủ, bố cục chung (Layout) phân chia thành các vùng chức năng chính bao gồm Sidebar điều hướng, Header, Content hiển thị bài hát và Footer tích hợp trình phát nhạc.
* Viết code xử lý giao diện phía Khách hàng: cho phép duyệt bài hát theo danh mục thể loại nhạc (Rap, Bolero, Pop, Ballad) và hiển thị chủ đề âm nhạc trực quan.
* Phát triển logic xử lý chức năng tìm kiếm bài hát theo từ khóa trên thanh công cụ.
* Xây dựng logic quản lý danh sách nhạc cá nhân: tạo danh sách phát (`Playlist`), thêm bài hát vào mục yêu thích hoặc thêm bài hát vào danh sách phát cá nhân.

## 2. Tài liệu liên quan
* Tài liệu hướng dẫn lập trình ASP.NET Routing và kiến trúc xử lý `ActionResult`, `PartialView`.
* Tài liệu kỹ thuật thao tác với đối tượng HTML qua DOM và thư viện xử lý đa kịch bản jQuery/JavaScript.
* Cơ chế lưu trữ cookie xác thực (`FormsAuthentication.SetAuthCookie`) phục vụ quá trình duy trì phiên đăng nhập của người nghe nhạc.

## 3. Khó khăn gặp phải
* Xử lý đồng bộ tiến trình phát nhạc, cập nhật thanh thời gian chạy (`audio.ontimeupdate`) và phần trăm tiến độ bài hát (`progressPercent`) ngay tại giao diện front-end mà không làm tải lại toàn bộ trang web khi người dùng thao tác phát/dừng nhạc.
* Áp dụng và triển khai code AJAX/jQuery tương tác không đồng bộ để xử lý chức năng thêm nhanh bài hát vào danh sách phát cá nhân trực tiếp từ giao diện thông tin bài hát.

## 4. Kết quả đạt được
* Chức năng đăng ký tài khoản mới và đăng nhập hệ thống vận hành đúng nghiệp vụ.
