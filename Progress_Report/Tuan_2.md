# Tuan_2.md
# 📑 BÁO CÁO TIẾN ĐỘ ĐỒ ÁN - TUẦN 2
* **ĐẠI HỌC TRÀ VINH**
* **Trường:** Kỹ thuật và Công nghệ
* **Bộ môn:** Công nghệ Thông tin 
* **Đề tài:** Xây dựng website Nghe nhạc trực tuyến trên nền tảng ASP.NET 
* **Sinh viên thực hiện:** Võ Thị Thiên Nga 
* **Mã số sinh viên:** 170125155 
* **Thời gian báo cáo:** 29/06/2026 - 05/07/2026
---

## 1. Nội dung công việc
Khảo sát thực tế các nhóm tính năng tương tác phổ biến và nhu cầu sử dụng thực tế của cộng đồng yêu nhạc trực tuyến.
Xác định yêu cầu chức năng nghiệp vụ của hệ thống cho hai phân hệ đối tượng chính: Người nghe nhạc (User) và Người quản lý (Admin).
Khảo sát chi tiết cấu trúc nhóm chức năng hệ thống bao gồm: Đăng nhập, đăng ký, tìm kiếm bài hát, quản lý danh sách phát cá nhân, quản lý ca sĩ, quản lý thể loại, quản lý chủ đề, và quản lý tài khoản hệ thống.
Tiến hành vẽ và thiết kế sơ đồ Use-case tổng quát cho toàn bộ hệ thống để phân rõ quyền hạn truy cập chức năng.
Thiết kế mô hình quan hệ dữ liệu hệ thống (Entity Relationship Diagram) để chuẩn bị hiện thực hóa cấu trúc bảng trên hệ quản trị cơ sở dữ liệu SQL Server.

## 2. Tài liệu liên quan
* Tài liệu phân tích và thiết kế hệ thống thông tin phần mềm.
* Tài liệu quản trị và hướng dẫn truy vấn hệ cơ sở dữ liệu quan hệ Microsoft SQL Server.
* Đặc tả chi tiết cấu trúc thuộc tính của các bảng nghiệp vụ cốt lõi: `Nhac`, `account`, `Playlist`, `TheLoai`, `CaSi`, `ChuDe`.

## 3. Khó khăn gặp phải
* Thiết kế, phân bổ các mối quan hệ ràng buộc và ràng buộc toàn vẹn (khóa chính/khóa ngoại) giữa bảng dữ liệu nhạc trung tâm (`Nhac`) với các bảng thành phần (`CaSi`, `TheLoai`, `ChuDe`) để tránh phân rã hoặc sai lệch thông tin bài hát.
* Đồng bộ và liên kết hệ thống phân quyền của thực thể tài khoản (`account`) thông qua thuộc tính `Role` nhằm phân biệt rõ ràng giữa quyền quản lý của Admin và quyền truy cập cá nhân hóa của User ngay từ tầng cơ sở dữ liệu.

## 4. Kết quả đạt được
* Xây dựng thành công sơ đồ cấu trúc dữ liệu tổng quan (Database Diagram).
* Hoàn thành thiết lập từ điển dữ liệu chi tiết cho toàn bộ 6 bảng nghiệp vụ cốt lõi lưu trữ trên SQL Server.
