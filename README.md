# Môn: Phát triển ứng dụng với mã nguồn mở-TEE0421
# VŨ ĐỨC TÚ     K225480106068
# Lớp: 58KTPM

# Bài tập 03:

# SỬ DỤNG WORDPRESS ĐỂ TẠO WEB SITE

# SSH ubuntu 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0f460bad-0e54-4ef0-82aa-00adb8a8d8aa" />

# 1.Chuẩn bị thư mục

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/54f1ee28-b466-4348-aa15-bbe9a7b726fa" />

# 2.Cài Docker

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3b05db8b-6df9-451b-8e07-2a6950ab9ad8" />

# 3. Tạo file docker-compose.yml

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ded3fa6e-7489-493b-bd6f-4157bd20ca8d" />

# 4.Chạy 3 service

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7a4b3653-257a-4e36-a89a-f21233fcdb02" />

# 5. Kiểm tra WordPress
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/472f1bb5-0c6b-4aad-b009-3a67adb0db58" />

# 6.Cài đặt WordPress lần đầu
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/583570f9-4c41-473a-9343-c08c65ff636b" />

# 7. Kiểm tra phpMyAdmin
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ae3f60c4-6a7e-4614-bfae-93c44dba7182" />

# 8. Public WordPress bằng Cloudflare Tunnel

## Vào Cloudflare tạo tunnel

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/368cc2fc-983c-43fe-8822-e529befd18eb" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/84733287-7226-4109-92ee-6f46625a9925" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/cbd60e83-5d28-4623-bc3c-45865c33b83d" />

# 9. Thêm cloudflared vào docker-compose.yml

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4c3d864d-0a82-4f38-ad26-9b90f394f550" />

## chạy lại dooker 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5c5c9996-8af8-47d4-8483-e07b1d7afa0a" />

# 10. Cấu hình subdomain trên Cloudflare

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/73b4d6d8-e352-42f4-bb76-f74aeff41184" />

# 11. Kiểm tra website public 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fb4fe1ba-7703-4775-ba2b-3e47a9372fbf" />

# 12. Tạo bài viết giới thiệu bản thân

## Chèn ảnh 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4a7a0c9f-091b-4ad7-8067-d872ea57a29f" />

## Chèn video 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8d7cdb90-6315-4b4f-a7f5-99f160dbb59e" />

## Chèn âm thanh 

<img width="1920" height="1068" alt="image" src="https://github.com/user-attachments/assets/6ef177f9-7d6b-4b68-9b68-ef9b7b6f8713" />

https://word.vuductu.id.vn/?p=6

# 13. TẠO BÀI VIẾT NGÀNH HỌC YÊU THÍCH

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c585f2c0-2b69-464b-8e90-7cfea6d761fc" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3caeab89-53d7-47e9-8807-02abf8e538a9" />

https://word.vuductu.id.vn/?p=10

# Kết quả 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/caeb312f-dbf2-45e6-97b5-94991b8de50b" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d56cc0b-16ab-44f5-b853-9cd8439b8d7a" />

# Nhận xét 

Qua quá trình triển khai website bằng mã nguồn mở WordPress trên Ubuntu sử dụng Docker, MariaDB, phpMyAdmin và Cloudflare Tunnel, em nhận thấy WordPress là một nền tảng mạnh và tương đối dễ sử dụng đối với người mới học phát triển web.

Ưu điểm lớn nhất của WordPress là dễ tạo và quản lý nội dung. Người dùng không cần lập trình quá nhiều vẫn có thể tạo website, đăng bài viết, chèn hình ảnh, video, âm thanh và quản lý giao diện thông qua trang quản trị trực quan. Ngoài ra WordPress có cộng đồng sử dụng rất lớn nên dễ tìm tài liệu và plugin hỗ trợ.

Trong quá trình triển khai, phần tốn nhiều công sức nhất phải là  Docker, Docker Compose, MariaDB, phpMyAdmin và Cloudflare Tunnel. Người triển khai cần hiểu về container, networking, port, domain và cơ sở dữ liệu để hệ thống hoạt động ổn định. Ban đầu việc cấu hình có thể khá khó với người mới, đặc biệt khi gặp các lỗi như xung đột port, sai cấu hình tunnel hoặc redirect domain.

Về tài nguyên máy chủ, WordPress sử dụng nhiều tài nguyên hơn so với website tĩnh do cần chạy đồng thời nhiều thành phần như Apache/PHP, MariaDB và phpMyAdmin. Trong quá trình thực hành, hệ thống có thể tiêu tốn vài trăm MB RAM và sử dụng CPU nhiều hơn khi có nhiều truy cập hoặc cài thêm plugin. Vì vậy nếu triển khai trên VPS thực tế cần có cấu hình phù hợp để tránh website bị chậm.

Một ưu điểm khác là WordPress là mã nguồn mở nên không mất phí bản quyền và có thể triển khai trên nhiều môi trường khác nhau. Khi kết hợp với Docker giúp việc triển khai, sao lưu và di chuyển hệ thống trở nên thuận tiện hơn. Ngoài ra Cloudflare Tunnel hỗ trợ public website ra Internet mà không cần IP public hoặc cấu hình NAT phức tạp.

Tổng kết lại, WordPress là nền tảng phù hợp cho việc xây dựng blog, website cá nhân hoặc website giới thiệu. Việc sử dụng Docker và Cloudflare giúp tăng tính linh hoạt và hiện đại trong triển khai hệ thống, tuy nhiên người dùng cần có kiến thức cơ bản về Linux và mạng để xử lý các lỗi phát sinh trong quá trình cấu hình.







