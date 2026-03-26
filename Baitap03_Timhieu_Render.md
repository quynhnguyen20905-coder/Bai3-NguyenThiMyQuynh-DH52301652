# BÀI TẬP 03: TÌM HIỂU VỀ RENDER VÀ TRIỂN KHAI TRANG WEB

**Họ và tên:** Nguyễn Thị Mỹ Quỳnh
**MSSV:** DH52301652
**Lớp:** [Tên lớp của bạn]
**Ngày nộp: 26/03/2026**

---

## PHẦN 1: TÌM HIỂU VỀ NỀN TẢNG RENDER

### 1.1. Render là gì?
Render là một nền tảng đám mây (Cloud Platform) hiện đại, được thiết kế để giúp các nhà phát triển triển khai (deploy), vận hành và mở rộng các ứng dụng web cũng như các trang web tĩnh (static websites) một cách dễ dàng và tự động. Render được xem là một lựa chọn thay thế mạnh mẽ cho Heroku nhờ vào tính đơn giản, hiệu năng cao và chi phí hợp lý (có gói miễn phí cho sinh viên và dự án nhỏ).

### 1.2. Các tính năng chính của Render
*   **Hỗ trợ đa dạng loại hình dịch vụ:** Tự động triển khai các trang web tĩnh (HTML/CSS/JS), các dịch vụ web (Node.js, Python, Go, Ruby, v.v.), cơ sở dữ liệu (PostgreSQL, Redis) và các ứng dụng Docker.
*   **Triển khai liên tục (Continuous Deployment - CD):** Kết nối trực tiếp với GitHub/GitLab. Mỗi khi bạn đẩy code (push) lên kho lưu trữ, Render sẽ tự động xây dựng (build) và cập nhật trang web mới nhất.
*   **Chứng chỉ SSL miễn phí:** Tự động cung cấp và gia hạn chứng chỉ bảo mật HTTPS thông qua Let's Encrypt, giúp trang web an toàn hơn.
*   **Global CDN:** Sử dụng mạng lưới phân phối nội dung toàn cầu để tăng tốc độ tải trang cho người dùng ở khắp mọi nơi.
*   **Xem trước Pull Request (Pull Request Previews):** Tự động tạo một liên kết xem trước cho mỗi yêu cầu thay đổi (Pull Request) để kiểm tra trước khi gộp vào bản chính.
*   **DDoS Protection:** Tích hợp sẵn các lớp bảo vệ chống lại các cuộc tấn công từ chối dịch vụ.

### 1.3. Ưu điểm của Render
*   **Dễ sử dụng:** Giao diện trực quan, không yêu cầu cấu hình máy chủ phức tạp.
*   **Miễn phí cho dự án nhỏ:** Gói Static Site hoàn toàn miễn phí với băng thông lên tới 100GB/tháng.
*   **Hiệu suất cao:** Hạ tầng hiện đại giúp ứng dụng chạy ổn định và nhanh chóng.

---

## PHẦN 2: CÁC BƯỚC TRIỂN KHAI TRANG WEB LÊN RENDER

### Bước 1: Chuẩn bị mã nguồn và Đẩy lên GitHub
Đảm bảo mã nguồn trang web (HTML, CSS và các thư mục hình ảnh) đã được đẩy lên kho lưu trữ GitHub.
*   **Link GitHub của project:** `https://github.com/quynhnguyen20905-coder/Bai3-NguyenThiMyQuynh-DH52301652`

### Bước 2: Đăng ký tài khoản Render
1.  Truy cập vào trang chủ [Render.com](https://render.com/).
2.  Chọn **Sign Up** và đăng ký thông qua tài khoản GitHub để đồng bộ hóa kho lưu trữ dễ dàng nhất.

### Bước 3: Tạo một Static Site mới trên Render
1.  Tại màn hình Dashboard, nhấn nút **New +** và chọn **Static Site**.
2.  Kết nối với tài khoản GitHub nếu chưa thực hiện.
3.  Tìm và chọn kho lưu trữ có tên: `Bai3-NguyenThiMyQuynh-DH52301652`.

### Bước 4: Cấu hình thông số triển khai
*   **Name:** Đặt tên cho dự án (ví dụ: `my-quynh-dh52301652`).
*   **Branch:** Chọn nhánh `main`.
*   **Root Directory:** Để trống (vì mã nguồn nằm ở thư mục gốc).
*   **Build Command:** Để trống (vì đây là trang web tĩnh thuần HTML/CSS).
*   **Publish Directory:** Để trống hoặc nhập `.` (vì file `index.html` nằm ở thư mục gốc).

### Bước 5: Triển khai và Kiểm tra
1.  Nhấn **Create Static Site**.
2.  Chờ đợi Render thực hiện quá trình Build và Deploy (thường mất khoảng 1-2 phút).
3.  Sau khi trạng thái chuyển sang **Live**, bạn sẽ nhận được một đường link (ví dụ: `https://my-quynh-dh52301652.onrender.com`).

---

## PHẦN 3: KẾT QUẢ VÀ ĐƯỜNG LINK KIỂM TRA

*   **Đường link GitHub Repo:** [https://github.com/quynhnguyen20905-coder/Bai3-NguyenThiMyQuynh-DH52301652](https://github.com/quynhnguyen20905-coder/Bai3-NguyenThiMyQuynh-DH52301652)
*   **Đường link Live Web (trên Render):** [Điền link của bạn tại đây]

---
*Tài liệu này tóm tắt quá trình tìm hiểu về nền tảng Render và các bước cụ thể để đưa trang web thiết kế từ bài tập 02 lên môi trường Internet.*
