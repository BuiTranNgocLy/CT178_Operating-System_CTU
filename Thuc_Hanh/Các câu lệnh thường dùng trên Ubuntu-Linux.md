# Danh sách các câu lệnh cơ bản trong Ubuntu

## 1. Các câu lệnh về thư mục & tập tin
* `pwd` In ra đường dẫn đến vị trí hiện tại đang đứng

* `ls` Hiển thị danh sách tập tin & thư mục trong thư mục hiện tại đang đứng
  * `ls -a`: hiển thị file ẩn ( có dấu `.` trước tên file)
  
* `cd` Thay đổi vị trí thư mục
  * `cd .`: di chuyển đến thư mục cha của thư mục hiện tại
  * `cd -`: đến thư mục trước khi di chuyển thư mục hiện tại
  * `cd` hoặc `cd ~`: di chuyển đến thư mục `/home/username`
  * `cd /`: di chuyển đến thư mục `root`
  * `cd <tên thư mục con>`: di chuyển đến thư mục con bên trong thư mục hiện tại
  * `cd <đường dẫn đến thư mục>`: di chuyển đến thư mục với đường dẫn cứng ( /home/lampv/Documents)
  
* `cp` sao chép tập tin hay thư mục đến một thư mục khác
  * `cp <tên tập tin> <tên thư mục>`: copy một tập tin vào một thư mục
  * `cp -r <tên thư mục nguồn> <tên thư mục đích>`: copy thư mục nguồn vào thư mục đích

* `mv` di chuyển tập tin đến một thư mục mới đồng thời đổi tên tập tin đó

* `rm` (remove) xóa tập tin hay thư mục
  * `rm <tên tập tin>`: xoá tập tin
  * `rm <tên thư mục>`: xoá một thư mục rỗng
  * `rm -r <tên thư mục>`: Xóa bất kỳ thư mục nào

* `mkdir <tên thư mục>`: tạo thư mục mới
* `touch <tên tập tin>`: tạo file mới
*  `man <tên câu lệnh>`: hiển thị hướng dẫn các câu lệnh
<hr>

## 2. Các câu lệnh về thông tin hệ thống

* `df` : hiển thị mức độ chiếm dụng không gian đĩa cứng của tập tin hệ thống ở tất cả các phân vùng được gắn kết. Đơn vị `1K` . Hiển thị đơn vị MB hay GB -> `df -h`

* `du` Hiển thị mức chiếm dụng không gian đĩa cứng ở thư mục hiện tại và các thư mục con.
  * `du -h` :kết quả hiển thị sử dụng đơn vị là KB, MB hay GB
  * `du -s` :hiển thị tổng dung lượng

* `free` hiển thị dung lượng RAM còn trống & đang được sử dụng
  * `free -h` :hiển thị cách dễ đọc với con người
  * `free -g` :hiển thị đơn vị dạng GB
  * `free -` :hiển thị đơn vị dạng MB

* `top` thông tin về hệ thống Linux của bạn, các tiến trình đang chạy và tài nguyên hệ thống, bao gồm: CPU, RAM, phân vùng Swap, và tổng số các tác vụ đang chạy.
  * `uname -a` :toàn bộ thông tin về tên máy tính, tên nhân kernel kèm theo số phiên bản và một vài chi tiết khác.

* `lsb_release -a` : Hiển thị phiên bản linux đang dùng.

* `adduser <tên user mới>` :thêm một user mới cho máy

* `passwd <tên user mới>` :thêm password cho người dùng mới


  
