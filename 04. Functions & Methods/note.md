Minimize số lượng Parameter

Số lượng của Function / Method Parameter
0 => Best possible option
1 => Very good possible option
2 => Use with caution
3 => Avoid if possible

> 3 => Always avoid

Output Parameter
Cố gắng tránh Output Argument - đặc biệt nếu chúng unexpected

Function Should Be Small
Function Should Do Exactly One Thing
"One Thing" = Different Operation + Different Level of Abstraction
"Level of Abstraction"
High Level - Không kiểm soát quá trình, chỉ quan tâm tới kết quả
Low Level - Kiểm soát quá trình

Function & Abstraction
Function should do work that's one level of abstraction below their name
Try not to mix Level of Abstraction

Giữ Function ngắn
Rule of Thumb
Extract Code cùng thực hiện một chức năng
Extract Code yêu cầu diễn giải nhiều hơn Code xung quanh nó

Don't Repeat Yourself (DRY)
Không viết cùng một Code nhiều hơn một lần

Cố gắng giữ Function Pure
Pure Function
Cùng một Input luôn trả về cùng một Output
Không có Side Effect

Side Effect là gì?
Side Effect là một hoạt động không chỉ tác động tới Function Input và thay đổi Function Output mà còn thay đổi hệ thống tổng thể / trạng thái chương trình
Side Effect không hoàn toàn là xấu - cần chúng trong chương trình. Nhưng Unexpected Side Effect cần tránh

Tránh Unexpected Side Effect
Naming matter! => Tên của Function nên chỉ ra tín hiệu hoặc ngụ ý rằng Side Effect có thể xảy ra

Xử lý Side Effect
Function không nên có bất kì Unexpected Side Effect nào
Nếu có / cần Side Effect
Chọn tên Function ngụ ý điều đó
Di chuyển Side Effect vào một Function / Place khác
