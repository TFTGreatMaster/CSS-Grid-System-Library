# CSS-Grid-System-Library
Hãy thêm box-sizing: border-box; vào trang web của bạn. Ví dụ:

<style> * { box-sizing: border-box; } </style>
Nếu thiếu thuộc tính trên thì các column của bạn có thể không nằm trên một chiều ngang.

Column là gì?

Column nghĩa là cột, được sử dụng để chứa nội dung/thành phần hiển thị trên website của bạn. Column sử dụng padding trái/phải để tạo nên gutters - rãnh ngăn cách giữa các column trong Grid layout. Column luôn luôn là con trực tiếp của Row.

Column được sử dụng với class "col", đi kèm theo đó là một số class "c-*" "m-*" và "l-*":

- c-*: nghĩa là column, prefix class này có tác dụng trên mobile. * từ 0 tới 12. Trong đó 0 được sử dụng để ẩn column, 1 - 12 tương ứng với độ rộng chúng ta muốn sử dụng cho column (trên cơ sở 12 columns trong Grid system)
- m-*: nghĩa là medium, prefix class này có tác dụng trên Tablet.
- l-*: nghĩa là large, prefix class này có tác dụng trên PC.
