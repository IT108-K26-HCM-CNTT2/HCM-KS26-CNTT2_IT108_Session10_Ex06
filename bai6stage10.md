# Bài tập: Plain Text và Rich Text

## Phần 1. Phân tích

### 1. Phân biệt Plain Text và Rich Text

- Plain Text là văn bản thô, chủ yếu chứa các ký tự văn bản. Ví dụ: file `.txt` và `.md`.
- Rich Text là văn bản có định dạng như font chữ, màu sắc, hình ảnh và bố cục. Ví dụ: file Word `.docx`.

Markdown là dạng văn bản thô có thêm các ký hiệu đơn giản để trình bày nội dung, chẳng hạn `#` dùng để tạo tiêu đề và `**...**` dùng để in đậm.

### 2. Những sai lầm của Nam

**Sai lầm 1: Dùng file Word để lưu tài liệu dự án trên GitHub.**

File `.docx` có cấu trúc phức tạp và chứa cả thông tin định dạng. Vì vậy, Git khó so sánh những thay đổi nhỏ trong file Word hơn so với file Markdown.

**Sai lầm 2: Nghĩ rằng Git xử lý file Word và file văn bản giống nhau.**

Git có thể quản lý phiên bản file Word, nhưng khi so sánh thay đổi thì nội dung trong file Word không dễ đọc. Với Markdown, Git Diff có thể chỉ ra dòng nào được thêm, sửa hoặc xóa, nên nhóm dễ theo dõi và hạn chế khó khăn khi hợp nhất thay đổi.

**Sai lầm 3: Chưa tận dụng khả năng xem tài liệu trên GitHub.**

GitHub có thể hiển thị file Markdown trực tiếp trên trình duyệt. Các thành viên trong nhóm có thể đọc tài liệu mà không cần tải file về mở bằng Word.

### 3. Vì sao Markdown nhẹ và dễ xử lý hơn?

Markdown thường có dung lượng nhỏ vì chỉ lưu văn bản và các ký hiệu định dạng đơn giản. File cũng dễ mở bằng Notepad hoặc VS Code, dễ so sánh bằng Git Diff và có thể xem trực tiếp trên GitHub.

Về tình huống mất một byte dữ liệu: không thể khẳng định file Word chắc chắn hỏng hoàn toàn nếu mất một byte, vì còn tùy vị trí dữ liệu bị lỗi. Tuy nhiên, do `.docx` có cấu trúc phức tạp, lỗi dữ liệu có thể khiến file khó mở hoặc bị hỏng. Markdown là văn bản thuần nên thường dễ đọc và khôi phục một phần hơn, nhưng nội dung của nó vẫn có thể bị sai hoặc mất khi dữ liệu bị hỏng.

## Phần 2. Hoàn thiện bằng StackEdit

Đề bài chưa kèm đoạn giới thiệu gốc trong file Word, nên em dùng đoạn giới thiệu mẫu về dự án GreenTech để minh họa việc chuyển sang Markdown.

### Nội dung file Markdown

# Giới thiệu dự án GreenTech

GreenTech là dự án của nhóm sinh viên, hướng đến việc sử dụng công nghệ để góp phần bảo vệ môi trường và xây dựng lối sống xanh.

## Mục tiêu

- Nâng cao ý thức bảo vệ môi trường.
- Khuyến khích sử dụng các giải pháp công nghệ xanh.
- Hạn chế rác thải và sử dụng tài nguyên hợp lý.

## Đối tượng hướng đến

Dự án hướng đến học sinh, sinh viên và những người quan tâm đến môi trường.

## Kết luận

Thông qua dự án GreenTech, nhóm mong muốn góp phần xây dựng môi trường sống xanh, sạch và bền vững.

### Các bước thực hiện

1. Mở trang https://stackedit.io/ bằng trình duyệt.
2. Tạo tài liệu mới và dán nội dung Markdown ở trên vào vùng soạn thảo.
3. Kiểm tra phần xem trước để xem tiêu đề và danh sách đã hiển thị đúng chưa.
4. Xuất hoặc tải tài liệu xuống dưới dạng Markdown và lưu tên file `GreenTech.md`.

### Kết quả

File `GreenTech.md` có nội dung đơn giản, dễ đọc và có thể đưa lên GitHub. Khi có chỉnh sửa, Git Diff cũng giúp các thành viên theo dõi phần nội dung thay đổi dễ hơn.

**Lưu ý:** Phần giới thiệu GreenTech ở trên là nội dung mẫu vì đề bài chưa cung cấp file Word gốc để chuyển đổi.
