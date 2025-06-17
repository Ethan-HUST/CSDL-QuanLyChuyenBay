
# 🛫 Cơ sở Dữ liệu Quản lý Chuyến bay – Bài tập lớn MI3090

## 🧾 Thông tin chung

- **Môn học**: Cơ sở Dữ liệu (MI3090)
- **Chủ đề**: Thiết kế và triển khai CSDL quản lý các chuyến bay của một hãng hàng không trong phạm vi quốc gia
- **Giảng viên hướng dẫn**: TS. Nguyễn Thị Thanh Huyền
- **Sinh viên thực hiện**: Nguyễn Trung Kiên – MSSV 20227180
- **Lớp học**: 150323
- **Thời gian**: 6/2024

## 🎯 Mục tiêu đề tài

- Xây dựng hệ cơ sở dữ liệu đầy đủ từ phân tích thực tiễn đến truy vấn SQL cho bài toán quản lý các chuyến bay.
- Áp dụng hai phương pháp: ánh xạ mô hình ER và chuẩn hóa (3NF) để thiết kế dữ liệu chặt chẽ.
- Phát triển tập câu truy vấn SQL phục vụ thống kê, phân tích và khai thác dữ liệu.

## 🧩 Nội dung chính

### 1. Phân tích bài toán thực tiễn
- Quản lý chuyến bay, lịch bay, hành khách, nhân viên, máy bay và đặt chỗ.
- Cơ sở dữ liệu phục vụ tự động hóa và tối ưu hóa vận hành hàng không.

### 2. Thiết kế hệ thống
- **Mô hình ER** (Entity-Relationship Diagram)
- **Ánh xạ sang mô hình quan hệ**
- **Chuẩn hóa đến 3NF**, đảm bảo không dư thừa dữ liệu và không mất mát thông tin

### 3. Cấu trúc các bảng chính
- `KHACHHANG`, `CHUYENBAY`, `NHANVIEN`, `MAYBAY`, `LOAIMB`, `DATCHO`, `LICHBAY`, `PHANCONG`, `KHANANG`

### 4. Truy vấn SQL nâng cao
- Tìm chuyến bay dài nhất, muộn nhất trong ngày
- Khách hàng đi nhiều nhất
- Số lượng loại máy bay, hãng sản xuất
- Phân tích số lượt đặt chỗ, nhân viên, hành khách, hiệu suất loại máy bay

## 🛠 Công nghệ sử dụng
- **Ngôn ngữ**: SQL
- **Hệ quản trị**: MySQL 8.0
- **Công cụ thiết kế**: MySQL Workbench, sơ đồ ERD
- **Trình bày & mô tả**: Word (.docx), Diagram, mã SQL, ảnh chụp thực thi

## 📁 Liên kết dữ liệu
- [📄 Báo cáo đầy đủ + mã nguồn](https://drive.google.com/drive/folders/1xDBcGI6itr3Y2N3Hlm0Y5bAV6WyLDYuK?usp=sharing)

## 📚 Kiến thức áp dụng
- Thiết kế dữ liệu thực tế
- Ánh xạ và chuẩn hóa quan hệ
- Viết truy vấn phân tích thống kê
- Bảo toàn dữ liệu & kiểm tra toàn vẹn
- Trình bày tài liệu kỹ thuật và báo cáo

## 🙏 Lời cảm ơn
Em xin chân thành cảm ơn cô **TS. Nguyễn Thị Thanh Huyền** đã tận tình giảng dạy, hướng dẫn em trong suốt quá trình học và thực hiện bài tập lớn. Bài báo cáo là thành quả của sự học hỏi và rèn luyện kiến thức chuyên ngành về cơ sở dữ liệu, áp dụng vào một bài toán thực tế mang tính ứng dụng cao trong ngành hàng không.

---
