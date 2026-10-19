# Bài 7: Gỡ Lỗi Tài Liệu Kế Hoạch Hội Nghị Khoa Học Sinh Viên
## Phần 1: Phân tích lỗi
### 1.	Xác định lỗi của từng dòng tiêu đề
**Nguyên nhân** là các tiêu đề chủ yếu chỉ được định dạng thủ công như in đậm, đổi cỡ chữ, tô màu hoặc sử dụng Normal. Word không nhận diện những định dạng này là tiêu đề để đưa vào mục lục tự động.
| Dòng tiêu đề |	Cấp Heading đúng |	Lỗi hiện tại|
|---|---|---|
| 1. Thông tin chung hội nghị |	Heading 1	| Chỉ in đậm, tăng cỡ chữ và tô vàng.|
| 1.1. Tên hội nghị |	Heading 2 |	Đang dùng Normal, chỉ in đậm và đổi cỡ chữ.|
| 1.2. Thời gian & địa điểm |	Heading 2 |	Đang dùng Normal.|
| 2. Cơ cấu ban tổ chức |	Heading 1	| Chỉ định dạng thủ công.|
| 2.1. Ban Nội dung |	Heading 2 |	Đang dùng Normal, có màu xanh.|
| 2.1.1. Tiểu ban Kỹ thuật |	Heading 3 |	Cần kiểm tra và gán đúng cấp Heading 3.|
| 3. Lịch trình sự kiện |	Heading 1 |	Đang dùng Normal, chưa có định dạng tiêu đề.|

**Cơ chế hoạt động:** Word dựa vào Heading 1, Heading 2 và Heading 3 để nhận diện tiêu đề khi tạo mục lục tự động. Nếu chỉ chỉnh sửa hình thức chữ mà không gán link Heading Styles, Word có thể không đưa các tiêu đề vào mục lục.
### 2.	Tại sao nhầm Heading 2 và Heading 3 làm mục lục sai?
Mỗi cấp Heading thể hiện một cấp độ nội dung khác nhau:

•	Heading 1: Tiêu đề chương.

•	Heading 2: Tiêu đề mục con.

•	Heading 3: Tiêu đề chi tiết nhỏ hơn.

Ví dụ:
- Heading 1: 2. Cơ cấu ban tổ chức
  
    - Heading 2: 2.1. Ban Nội dung
  
        -	Heading 3: 2.1.1. Tiểu ban Kỹ thuật
  
Nếu gán sai cấp Heading, tiêu đề sẽ bị thụt đầu dòng không đúng vị trí trong mục lục, khiến người đọc khó phân biệt chương, mục và chi tiết.
## Phần 2: Sửa lỗi & Nghiệm thu
### 1.	Các bước sửa Heading cho 7 dòng tiêu đề
Bước 1: Mở file Word và tìm từng dòng tiêu đề cần sửa.

Bước 2: Đặt con trỏ vào từng dòng tiêu đề và sử dụng phím tắt sau:
| Dòng tiêu đề	| Phím tắt|
|---|---|
| 1. Thông tin chung hội nghị |	Ctrl + Alt + 1|
| 1.1. Tên hội nghị |	Ctrl + Alt + 2|
| 1.2. Thời gian & địa điểm |	Ctrl + Alt + 2|
| 2. Cơ cấu ban tổ chức |	Ctrl + Alt + 1|
| 2.1. Ban Nội dung	| Ctrl + Alt + 2|
| 2.1.1. Tiểu ban Kỹ thuật	| Ctrl + Alt + 3|
| 3. Lịch trình sự kiện |	Ctrl + Alt + 1|

Bước 3: Sau khi gán Heading xong, đặt con trỏ tại trang đầu, chọn References → Table of Contents → Automatic Table để tạo mục lục tự động.

Bước 4: Kiểm tra mục lục đã hiển thị đủ ba cấp Heading và các tiêu đề được thụt đầu dòng đúng thứ tự hay chưa.
### 2.	Cập nhật số trang trong mục lục
Khi tiêu đề “3. Lịch trình sự kiện” chuyển từ trang 2 sang trang 4, mục lục có thể vẫn hiển thị số trang cũ nếu chưa được cập nhật.
Cách thực hiện:
1.	Nhấp vào mục lục.
2.	Chọn Update Table.
3.	Chọn Update page numbers only nếu chỉ thay đổi số trang; hoặc Update entire table nếu có thay đổi cả tiêu đề và cấu trúc.
4.	Nhấn OK.

