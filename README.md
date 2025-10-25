# BT2-Lap-trinh-web 
# Sinh Viên: Lê Tuấn Anh - K225480106001
# Bài làm
## 1.Cài đặt Apache
a) Đưa Apache vào ổ C:
b) Cấu hình các file yêu cầu:
c) Fake IP cho letuananh.com
d) Cài và khởi động Apache, đồng thời test:
## 2. Cài đặt nodejs và nodered
a) Cài đặt nodejs và check phiên bản:
b) Cài đặt Nodered
c) Cài đặt file, khởi chạy service a1-
## 3. Tạo database ngẫu nhiên:
## 4. Cài đặt thư viện
a) Cài đặt thư viện nodered bằng các câu lệnh(hình dưới là ví dụ cho 1 thư viện, các cái còn lại làm tương tự):
b) Hash PW và sửa vào setting.js:
c) Khởi động lại service sau đó đăng nhập nodered: 
## 5. Tạo API BE bằng nodered
a) Thiết kế flow: 
b) Code truy vấn cho node Function (viết vào mục On message)
msg.payload = {
    query: "SELECT * FROM dongvat"
};
return msg;
c) Cấu hình để kết nối với DB qua localhost (dùng tài khoản sa):
d) Kiểm tra dữ liệu trả về từ DB: 
## 6. Tạo FE 
- Tạo folder chứa các ngôn ngữ để làm FE theo yêu cầu.
- FE sẽ gọi API từ BE Nodered
- Kết quả trả về như sau:

## 7. Nhận xét bài làm


