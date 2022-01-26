# tran-manh-dat-fresher-camp
 Bài tập chia theo từng branch.

# Khóa chính(Primary Key)
-Khoá chính hay còn gọi là primary key được sử dụng để định danh một dòng dữ liệu duy nhất trong một bảng. 
-Giá trị của khoá chính phải có giá trị duy nhất, không trùng lặp với các khoá chính của các dòng dữ liệu khác.
-Ngoài ra giá trị của khoá chính phải khác null.
# Vì sao dùng ID là số tự tăng?
-AUTO_INCREMENT chỉ thiết lập được cho kiểu INT và mỗi bảng chỉ có một field duy nhất, nghĩa là nếu bạn thiết lập 2 fields là AUTO_INCREMENT thì sẽ bị lỗi.
-Khi bạn thêm dữ liệu nếu bạn có truyền data thì nó sẽ lấy data đó thay vì tăng tự động, ngược lại nó sẽ lấy giá trị lớn nhất hiện tại và tăng lên 1(giá trị lớn nhất này lưu trong config của table chứ không phải là id lớn nhất trong các records).
-Khi bạn xóa một record thì sẽ bị khuyết mất một giá trị, lúc này nếu bạn thêm thì nó sẽ không lấp vào vị trí này mà nó tuân theo quy luật trên.

Thông thường ta sử dụng AUTO_INCREMENT cho Primary Key khi viết ứng dụng website
Mặc định AUTO_INCREMENT sẽ có giá trị đầu tiên là 1

# Khi nào sử dụng khóa chính :
-Khi cần đảm bảo tính độc nhất của dữ liệu.
-
