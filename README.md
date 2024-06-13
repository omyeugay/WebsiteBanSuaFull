# WebsiteBanSua
1. Tải sourcecode về giải nén
2. Cấu hình databse theo file .env
3. Tạo CSDL websitebansua -> Import database (DATABASE ở thư' mục databse/websitebansua14052019.sql)
4. Cấu hình Login facebook, google, github, twitter, ... tại file .env hoặc config/services.php
5. Các app để login của facebook, google, github, twitter đã lâu không chạy nên có thể bị chết. Bạn có thể setup app mới.
6. Bạn phải cài đặt server như xampp hoặc laragon, composer, git bash trước khi dùng.
7. Bạn chạy git bash trong project và chạy lệnh: php artisan serve. Sau đó bạn có thể vào link http://localhost:8000/ để chạy
website
8. Nếu như bạn có thay đổi url của web site thì phải thay đổi cả biến APP URL trong file .env (cuối url không có dấu /)
9. Nếu như hình ảnh trên website không hiển thị thì hãy xóa folder storage trong thư mục \public, sau đo chạy url
websitecuaban.local/clear-cache để xóa cache , config và tạo lại srotage:link
10. Đăng nhập người dùng ở trang chủ, bạn có thể tự đăng ký để dùng. http://localhost:8000/login
11. Chức năng kích hoạt tài khoản qua email sau khi đăng ký đã bị tắt, bạn có thể bật lại nếu muốn.
12. Đăng nhập admin tại: http://localhost:8000//admin . User/pass: 123456/1234560
13. Update: Chạy url http://localhost:8000/clear-cache để xoa cache và config đi nhé.

Mọi thắc mắc các bạn có thể liên hệ với mình qua số điện thoại SAU KHI MUA CODE
Lưu ý:
- Xóa file config.php trong bootstrap/cache/config.php nếu xảy ra lỗi.
