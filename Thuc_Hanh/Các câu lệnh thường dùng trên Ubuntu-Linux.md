# Danh sách các câu lệnh cơ bản trong Ubuntu

## 1. Các câu lệnh về thư mục & tập tin
* `pwd` In ra đường dẫn đến vị trí hiện tại đang đứng
* `ls` Hiển thị danh sách tập tin & thư mục trong thư mục hiện tại đang đứng
  * `ls -a`: hiển thị file ẩn
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
