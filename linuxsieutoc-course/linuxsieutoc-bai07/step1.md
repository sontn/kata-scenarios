Trước khi copy thư mục/file, các bạn sẽ tạo thư mục và file rồi copy nhé. Các bạn gõ lệnh `mkdir -p a/b/`{{execute}}, và tạo 1 file **c** trong thư mục b là thư mục con của a bằng câu lệnh `touch a/b/c`{{execute}}


Giờ các bạn copy cả thư mục a, bao gồm thư mục b và file c, đến thư mục /tmp, các bạn gõ lệnh `cp -r a /tmp`{{execute}}


Các bạn kiểm tra lại kết quả bằng câu lệnh `ls /tmp`{{execute}}


Để đổi tên thư mục/file, các bạn sử dụng câu lệnh **mv**. Ví dụ `mv /tmp/a /tmp/A`{{execute}}

