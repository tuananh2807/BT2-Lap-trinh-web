# BT2-Lap-trinh-web 
# Sinh Viên: Lê Tuấn Anh - K225480106001
# Bài làm
## 1.Cài đặt Apache
a) Đưa Apache vào ổ C:
<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/1d49e77e-ef4f-46c6-b183-8fea95f3dffb" />

b) Cấu hình các file yêu cầu:
<img width="944" height="648" alt="image" src="https://github.com/user-attachments/assets/ecfc081b-e4b5-460a-aa24-7c58431cc79b" />

c) Fake IP cho letuananh.com
<img width="944" height="648" alt="image" src="https://github.com/user-attachments/assets/66710b0a-7e56-45c7-af11-55462884b8bd" />

d) Cài và khởi động Apache, đồng thời test:
<img width="1103" height="639" alt="image" src="https://github.com/user-attachments/assets/254de197-dc4e-4444-b01b-1b59da342b8b" />

## 2. Cài đặt nodejs và nodered
a) Cài đặt nodejs và check phiên bản:
<img width="1103" height="639" alt="image" src="https://github.com/user-attachments/assets/8b188d40-11ec-43ea-b4d0-67f7f27d718b" />

b) Cài đặt Nodered
<img width="1103" height="639" alt="image" src="https://github.com/user-attachments/assets/be283513-cf8e-4032-92e8-9b045ebeec0a" />

c) Cài đặt file, khởi chạy service a1-
<img width="1103" height="639" alt="image" src="https://github.com/user-attachments/assets/26f2a78f-07bb-44b8-97d4-a50889f9afb4" />

## 3. Tạo database ngẫu nhiên:
<img width="1920" height="1039" alt="image" src="https://github.com/user-attachments/assets/2a04c163-0bd6-43ac-a36e-4072ebd194eb" />

## 4. Cài đặt thư viện
a) Cài đặt thư viện nodered bằng các câu lệnh(hình dưới là ví dụ cho 1 thư viện, các cái còn lại làm tương tự):
<img width="1066" height="267" alt="image" src="https://github.com/user-attachments/assets/a2bb2aa7-7483-48bd-9aad-e9b2320bda3b" />

b) Hash PW và sửa vào setting.js:
<img width="931" height="214" alt="image" src="https://github.com/user-attachments/assets/4e5d4808-7d44-4b94-b731-f3087867fb60" />

c) Khởi động lại service sau đó đăng nhập nodered: 
<img width="1875" height="891" alt="image" src="https://github.com/user-attachments/assets/9b6f1f7e-4d1d-41bc-9629-d69ae5d2a53d" />

## 5. Tạo API BE bằng nodered
a) Thiết kế flow: 
<img width="1166" height="606" alt="image" src="https://github.com/user-attachments/assets/789ed696-ead8-4295-8660-dcb0571ef3a5" />

b) Code truy vấn cho node Function (viết vào mục On message)
msg.payload = {
    query: "SELECT * FROM dongvat"
};
return msg;
c) Cấu hình để kết nối với DB qua localhost (dùng tài khoản sa):
<img width="633" height="776" alt="image" src="https://github.com/user-attachments/assets/1b1d527f-eb22-4428-ad5c-c2198d6a1afa" />

d) Kiểm tra dữ liệu trả về từ DB: 
<img width="1917" height="982" alt="image" src="https://github.com/user-attachments/assets/41073aa9-b586-485a-a1a2-d04f25ab6c5e" />

## 6. Tạo FE 
- Tạo folder chứa các ngôn ngữ để làm FE theo yêu cầu.
- FE sẽ gọi API từ BE Nodered
- Kết quả trả về như sau:
<img width="984" height="782" alt="image" src="https://github.com/user-attachments/assets/33f68d5a-a3fa-4b5f-8f05-94674294fa47" />


## 7. Nhận xét bài làm


