**Bước 1**: Xem xét ảnh kết quả mong muốn (outcome image)
Bạn cần dựa vào ảnh kết quả mong muốn được cung cấp trong đề bài (được mô tả là desired outcome) để nhận biết các phần tử có kiểu dáng tương tự (nên sử dụng class) và các phần tử nào là độc nhất (nên sử dụng ID).
Ngoài ra, có những phần tử có các thay đổi nhỏ so với phần khác, nghĩa là chúng sẽ cần có nhiều class.
**Bước 2**: Thêm thuộc tính class và ID vào các phần tử HTML
Bạn sẽ phải thêm các thuộc tính class hoặc ID vào các phần tử được yêu cầu trong file HTML. Ví dụ:
Tất cả các phần tử có số thứ tự lẻ (odd-numbered) sẽ cần có cùng một lớp (class).
Các phần tử có số thứ tự chẵn (even-numbered) sẽ có ID duy nhất.
**Bước 3**: 
Thêm quy tắc CSS với cú pháp đúng
Sau khi thêm các thuộc tính class và ID, bạn sẽ phải áp dụng các quy tắc CSS tương ứng bằng cách sử dụng đúng cú pháp của selectors. 
Cụ thể:
Tất cả các phần tử có số thứ tự lẻ phải có nền màu đỏ nhạt hoặc hồng, đồng thời có danh sách font chữ gồm Verdana và DejaVu Sans, và có sans-serif làm font dự phòng.
Phần tử thứ 2 phải có chữ màu xanh và kích thước font 36px.
Phần tử thứ 3, ngoài các kiểu dành cho các phần tử lẻ, còn phải có kích thước font 24px.
Phần tử thứ 4 phải có nền màu xanh nhạt, kích thước font 24px, và chữ in đậm.
**Bước 4**: Lời khuyên
Bạn có thể sử dụng các giá trị màu không phải là từ khóa (ví dụ như RGB, HEX, hoặc HSL) để tạo màu cho các phần tử.
Trong VS Code, bạn có thể thay đổi định dạng của màu bằng cách di chuột lên giá trị màu trong CSS và chọn định dạng mong muốn (RGB, HEX, HSL).
Kiểm tra lại công việc (Self Check):
Các phần tử p có số thứ tự lẻ có chia sẻ chung một lớp (class) không?
Các phần tử div có số thứ tự chẵn có ID riêng biệt không?
Phần tử thứ 3 có nhiều class không?