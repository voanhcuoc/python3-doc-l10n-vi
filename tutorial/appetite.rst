.. _tut-intro:

**********************
Khai vị
**********************

Nếu bạn làm việc nhiều với máy vi tính, một lúc nào đó bạn sẽ nhận thấy bạn
muốn tự động hóa một số việc. Ví dụ, bạn muốn thực hiện một phép tìm kiếm và
thay thế với nhiều file text, hoặc đổi tên và sắp xếp một loạt các file ảnh theo
một cách phức tạp. Có thể bạn muốn viết cơ sở dữ liệu tùy biến nho nhỏ,
hoặc một ứng dụng với giao diện đồ họa đặc biệt, hay một trò chơi đơn giản. 

Nếu bạn là một nhà phát triển phần mềm chuyên nghiệp, bạn có thể làm việc với
nhiều thư viện C/C++/Java nhưng bạn nhận thấy thường lặp đi lặp lại việc
viết/biên dịch/thử/biên dịch là quá tốn thời gian. Có thể bạn viết một bộ
các test cho các thư viện ấy và nhận ra rằng viết code để thử nghiệm là một
việc chán ngấy. Hoặc có thể bạn viết một chương trình cần sử dụng một ngôn ngữ
mở rộng, và bạn không muốn thiết kế, xây dựng cả một ngôn ngữ mới cho ứng dụng của mình. 

Python chính là ngôn ngữ lập trình bạn cần. 

Bạn có thể viết một Unix shell script hoặc Windows batch file cho các công việc
kiểu này, nhưng shell script chỉ tốt cho việc di chuyển các file lòng vòng và
sửa đổi các dữ liệu văn bản, nó không thích hợp cho một ứng dụng GUI hoặc một
trò chơi. Bạn cần viết một chương trình bằng C/C++/Java, nhưng nó có thể tiêu tốn
nhiều thời gian cho việc phát triển thậm chí từ bản nháp đầu tiên của chương trình.
Sử dụng Python đơn giản hơn, chạy được cả trên Windows, MacOS X, các hệ điều hành
Unix, và nó cũng giúp bạn hoàn thành công việc nhanh hơn. 

Sử dụng Python thì đơn giản, nhưng nó là một ngôn ngữ lập trình thực sự, cung cấp
nhiều cấu trúc hơn và hỗ trợ các chương trình lớn hơn so với các ngôn ngữ shell
hoặc Windows batch file. Mặt khác, Python cũng hỗ trợ nhiều phép kiểm tra lỗi hơn C,
và, là một *ngôn ngữ bậc-rất-cao*, nó có sẵn các kiểu dữ liệu cấp cao, như các mảng
và các dictionary linh hoạt. Chính vì nhiều kiểu dữ liệu tổng quát của nó Python
được ứng dụng rộng rãi hơn Awk hoặc thậm chí là Perl trong nhiều loại công việc
khác nhau, do đó có nhiều việc làm bằng Python cũng dễ dàng như làm bằng các ngôn ngữ khác.

Python cho phép bạn chia nhỏ chương trình của mình ra thành các module để có thể
sử dụng lại trong các chương trình Python khác. Nó có sẵn rất nhiều các module
chuẩn để bạn có thể sử dụng làm cơ sở cho chương trình của mình -- hoặc là các
ví dụ để bắt đầu học lập trình bằng Python. Một vài module trong số chúng cung cấp
các chức năng như file I/O (vào/ra), các system call, các socket, và thậm chí
các interface với các GUI toolkit như Tk.

Python là một ngôn ngữ thông dịch, điều đó giúp bạn tiết kiệm thời gian trong
quá trình phát triển chương trình vì việc biên dịch hay liên kết là không cần thiết.
Bộ thông dịch có thể được dùng một cách tương tác, làm cho việc thử nghiệm các
tính năng của ngôn ngữ trở nên dễ dàng, viết các chương trình bỏ đi, hoặc thử các
hàm trong việc phát triển chương trình từ dưới lên. Nó cũng là một máy tính
cầm tay tiện lợi. 

Python cho phép viết các chương trình súc tích và dễ đọc. Các chương trình viết
bằng Python thường ngắn hơn so với các chương trình viết bằng C, C++ hoặc Java,
vì nhiều lý do:

* các kiểu dữ liệu cao cấp cho phép bạn thực hiện nhanh các thao tác phức tạp
  chỉ với một lệnh đơn giản; 

* các lệnh được nhóm lại bằng khoảng cách thụt đầu dòng thay vì đóng mở bằng
  các dấu ngoặc; 

* không cần khai báo biến hoặc tham số trước khi sử dụng. 

Python có tính *mở rộng*(extensible): nếu bạn biết lập trình C thì rất dễ để
bổ sung các hàm hoặc module built-in vào bộ thông dịch, cũng như việc thực hiện
các thao tác quan trọng ở tốc độ tối đa, hoặc liên kết các chương trình Python
với các thư viện chỉ được cung cấp dưới dạng nhị phân (ví dụ như các thư viện
đồ họa của một vài nhà sản xuất). Một khi bạn đã thực sự móc nối, bạn có thể
liên kết bộ thông dịch Python vào trong các ứng dụng viết bằng C và sử dụng
nó như một extension hoặc ngôn ngữ lệnh cho ứng dụng đó. 

Cũng xin nói luôn, tên của ngôn ngữ này được đặt sau khi BBC phát chương trình
"Monty Python's Flying Circus" và nó không có liên quan gì với những loài bò sát.
Những tham khảo mang tính trào phúng tới Monty Python trong tài liệu không chỉ
được cho phép, mà còn được cổ vũ. 

Bây giờ khi tất cả các bạn đã bị kích thích về Python, bạn sẽ muốn khám phá nó
kỹ hơn. Cách học một ngôn ngữ tốt nhất là hãy sử dụng nó, tutorial này mời gọi
bạn hãy vừa đọc vừa thử trình thông dịch Python. 

Trong chương tiếp theo, các kĩ thuật sử dụng bộ thông dịch sẽ được giải thích.
Điều này không đơn thuần là thông tin, nó còn cần thiết cho việc thử các ví dụ
được trình bày về sau. 

Phần còn lại của tutorial sẽ giới thiệu các tính năng khác nhau của ngôn ngữ
Python và hệ thống thông qua các ví dụ, bắt đầu với các biểu thức đơn giản,
các câu lệnh và các kiểu dữ liệu, đi qua các hàm và các module, và kết thúc là
tiếp cận với các khái niệm cao cấp như *exception* và các *user-defined class*. 

