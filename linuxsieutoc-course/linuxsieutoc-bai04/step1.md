Đường dẫn tuyệt đối là đường dẫn bắt đầu từ vị trí thư mục gốc cho đến vị trí thư mục/file cần đến, ví dụ: **/etc/ssh**

Đường dẫn tương đối là đường dẫn bắt đầu từ vị trí hiện tại cho đến vị trí thư mục/file cần đến, ví dụ nếu các bạn đang đứng ở **/etc**, các bạn chỉ cần gõ **cd ssh** là vào thư mục **ssh** là thư mục con nằm trong thư mục **/etc**

Như vậy đường dẫn tuyệt đối sẽ bắt đầu bởi dấu **/**, còn đường dẫn tương đối thì không


Các bạn hãy thử ví dụ sau đây để hiểu hơn về đường dẫn tuyệt đối nhé:


Các bạn gõ lệnh `cd /etc`{{execute}}, câu lệnh này luôn thực thi được. Đây là đường dẫn tuyệt đối


Giờ tiếp tục, các bạn gõ lệnh `cd `{{execute}}, sau đó gõ lệnh tiếp `cd etc`{{execute}}, sẽ có thông báo lỗi như sau `-bash: cd: etc: No such file or directory`. Lỗi này tại sao vậy các bạn? Giờ các bạn gõ lệnh `pwd`{{execute}} và `ls`{{execute}} để tìm câu trả lời. Câu trả lời là trong thư mục **/root** không có thư mục **etc**


Giờ các bạn đã phân biệt được lệnh **cd /etc** và **cd etc** rồi đấy!