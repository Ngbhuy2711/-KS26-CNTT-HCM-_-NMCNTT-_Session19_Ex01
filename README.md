# phần 1 : phân tích ký tự lạ và cơ chế đánh lừa
- ký tự lạ URL : từ ú nằm trong tên miền githúb.com
- Cơ chế đánh lừa
  + hacker lợi dụng hệ thống tên miền quốc tế hóa cho phép sử dụng ký tự unicode trong địa chỉ web. Chúng đăng ký một tên miền có hình dáng gần như trùng khớp hoàn toàn với trang chính thức
  + tại sao ng dùng dễ sập bẫy : mắt người có xu hướng nhận diện từ ngữ theo tổng thể thay vì xem từng ký tự nhỏ
# phần 2 : quy trình kiểm tra URL trước khi nhập masterpassword 
1. kiểm tra bằng mắt thường
 - xem từng ký tự phần tên miền chính : tập trung vào đoạn ngay trước dấu .com và .vn đảm bảo ko có dấu phụ
 - kiểm tra đuôi miền : các tên miền ví dụ như github-security.com, git-hub.com, hay githúb.com là fake 100% vì github chỉ sử dụng tên miền gốc là github.com
2. sử dụng passwword manager
   
