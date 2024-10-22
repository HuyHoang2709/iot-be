### Các bước chạy dự án

1. Tải code về
   `git clone <link dự án>`
2. Cài Node.js (version >= 20)
3. Cài các thư viện
   `npm i`
4. Chạy dự án (ở cổng 8080, tự động lắng nghe thay đổi, không cần chạy lại lệnh này khi thực hiện thay đổi trên code)
   `npm start`

### Quy tắc

1. Các key mật (Tài khoản, mật khẩu, access token cho db,...) để vào file .env và lôi ra dùng qua thư viện dotenv (tự xem hướng dẫn trên mạng)
2. Cấu trúc thư mục Express\
   [Xem tại đây](https://viblo.asia/p/best-practices-for-expressjs-part-i-L4x5xgQqlBM)
3. Công nghệ sử dụng (đọc qua phần dependencies trong file `package.json`)
- jwt cho xác thực
- dotenv lưu key mật
- express để chạy server
- uuid gen unique key (optional)
- middleware bằng body-parser, cookie-parser
- pg để giao tiếp với postgre
- mqtt để nhận dữ liệu từ HiveMQ (1 MQTT Broker online, tham khảo từ bài thực hành)
- Dùng thêm cors trong xác thực (cho việc gửi cookie). Tìm hiểu thêm qua video của F8 (trong link tham khảo)
