# Clean Code - Checklist

## Naming

1 - Chọn tên có tính mô tả

2 -
Danh từ cho Variable và Property (hoặc cụm từ ngắn với Tính từ)
Danh từ cho Class
Động từ cho Method (hoặc cụm từ ngắn với Tính từ)

3 - Cụ thể nếu có thể nhưng không dư thừa

4 - Tránh tiếng lóng, viết tắt không rõ ràng và sử dụng tên một cách thống nhất

## Comment & Formatting

1 - Đa phần Comment là không tốt - tránh Comment!
Có thể thêm "good" Comment (thông tin pháp lý, cảnh báo, giải thích bắt buộc, todos)

2 - Sử dụng Vertical Formatting (Blank Line, Line Break) để giữ các khái niệm liên quan gần nhau (Vertical Density) và phân tách các khái niệm không liên quan mật thiết (Vertical Distance)

3 - Giữ dòng ngắn (Horizontal Formatting), thêm Line Break để nâng cao khả năng đọc và sử dụng Indentation

4 - Tuân thủ Language-Specific Style Guide (e.g PEP8 với Python) và sử dụng IDE auto-formatting để "generate" Clean Code

## Function

1 - Giới hạn số lượng tham số Function sử dụng - tìm cách giảm thiểu số lượng (e.g sử dụng Dictionary hoặc Object làm "Value Container")

2 - Clean Function nên nhỏ và "do only one thing"

3 - Khám phá Level of Abstraction của Function Code để làm giảm khoảng cách lớn giữa tên Function và Code thực sự cũng như tránh sử dụng lẫn lộn Level of Abstraction trong một Function

4 - Viết DRY Code và tránh Unexpected Side Effect

## Control Structure

1 - Ưu tiên Positive Wording

2 - Tránh Deep Nesting - ví dụ bằng cách sử dụng "Guard" hoặc bằng cách trích xuất Control Structure vào Function riêng biệt

3 - Cân nhắc sử dụng Polymorphism và Factory Function để tránh trùng lặp Code

4 - Sử dụng "Real Error" thay vì "Synthetic Error" được mô phỏng với câu lệnh if

## Object

1 - Sử dụng "Real Object" hoặc Data Structure / Container - tùy theo từng trường hợp cụ thể

2 - Clean Class nên nhỏ: Tập trung vào One Responsibility (KHÔNG có nghĩa là "One Method"!)

3 - Tuân thủ "Law of Demeter" khi làm việc với Real Object

4 - Cân nhắc tuân thủ SOLID Principle, đặc biệt là SRP và OCP
