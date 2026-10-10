# [Thực hành] Xây dựng Trang Chủ với Bootstrap

Dự án bài thực hành **Xây dựng Trang Chủ (Homepage) với Bootstrap**, ứng dụng bố cục linh hoạt, Display Property, Margin & Padding, Flexbox, Carousel trình chiếu hình ảnh, icon Font Awesome 6 và Contact Form.

---

## 🎯 Mục Tiêu Bài Thực Hành

- Luyện tập sử dụng **Bootstrap 5.3** để xây dựng bố cục website linh hoạt và đáp ứng (responsive).
- Ứng dụng thành thạo các tiện ích:
  - **Display Property & Flexbox**: `d-flex`, `justify-content-center`, `align-items-center`.
  - **Margin & Padding**: `mb-*`, `mt-*`, `py-*`, `px-*`.
  - **Carousel**: Trình chiếu slide hình ảnh tự động chuyển động với indicators và nút điều hướng.
  - **Font Awesome 6**: Nhúng icon sinh động vào thanh Navbar, tiêu đề và các trường biểu mẫu.
  - **Bootstrap Form**: Tạo biểu mẫu liên hệ chuẩn UI với `form-control`, `form-label` và nút gửi `btn-primary`.

---

## 📋 Các Bước Triển Khai Trong Bài Tập

### Bước 1: Cài đặt Bootstrap & Font Awesome
- Nhúng **Bootstrap 5.3.3 CSS** vào thẻ `<head>`:
  ```html
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  ```
- Nhúng **Font Awesome 6.5.2 CSS** vào thẻ `<head>`:
  ```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
  ```
- Nhúng **Bootstrap 5.3.3 JS Bundle** trước khi đóng thẻ `</body>`:
  ```html
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  ```

### Bước 2: Tạo Navbar với Font Awesome
- Sử dụng `.navbar.navbar-expand-lg.navbar-dark.bg-dark`.
- Thêm logo thương hiệu chứa icon `<i class="fas fa-home"></i> MyWebsite`.
- Danh sách liên kết điều hướng: Home, About, Services, Contact với icon trực quan.

### Bước 3: Tạo Hero Section với Carousel
- Sử dụng `#heroCarousel.carousel.slide` với `data-bs-ride="carousel"`.
- 3 slide hình ảnh chất lượng cao hiển thị toàn chiều rộng (`d-block.w-100`).
- Tích hợp `carousel-indicators`, `carousel-caption` và các nút điều khiển chuyển slide (`carousel-control-prev`, `carousel-control-next`).

### Bước 4: Thêm Section với Flexbox
- Căn giữa nội dung chào mừng hoàn hảo bằng lớp Flexbox:
  ```html
  <div class="d-flex justify-content-center align-items-center bg-light py-5">
      <h2>Chào mừng đến với trang web của chúng tôi!</h2>
  </div>
  ```

### Bước 5: Tạo Contact Form với Bootstrap Form
- Biểu mẫu liên hệ chuyên nghiệp đặt trong container với các trường:
  - **Tên của bạn** (`input[type="text"].form-control`)
  - **Email** (`input[type="email"].form-control`)
  - **Tin nhắn** (`textarea.form-control`)
  - **Nút gửi** (`button.btn.btn-primary`)

---

## 📁 Cấu Trúc Thư Mục

```plaintext
d:/BaiTapGithub/
├── .gitignore          # Cấu hình bỏ qua các tệp không cần thiết khi quản lý phiên bản
├── README.md           # Tài liệu hướng dẫn và mô tả bài thực hành
└── index.html          # Mã nguồn trang chủ Bootstrap hoàn chỉnh
```

---

## 🚀 Hướng Dẫn Chạy Trang Web

1. **Xem trực tiếp**: Nhấp đúp vào file `index.html` hoặc chuột phải chọn **Open with** -> **Google Chrome** / **Microsoft Edge**.
2. **Xem qua Live Server**: Chuột phải vào `index.html` trong IDE và chọn **Open with Live Server** (`http://127.0.0.1:5500/index.html`).

---

## 👨‍💻 Thông Tin Học Viên

- **Họ và tên**: dtc245200059
- **Email**: dtc245200059@ictu.edu.vn
- **Bài thực hành**: Xây dựng Trang Chủ với Bootstrap
