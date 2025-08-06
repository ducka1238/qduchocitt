# Duck Soft - Personal Tech Platform

## Giới thiệu
Duck Soft là nền tảng công nghệ cá nhân của Đồng Quang Đức, sinh viên Công nghệ Thông tin. Website cung cấp các công cụ hữu ích, blog chia sẻ kinh nghiệm và tin tức công nghệ.

## Tính năng chính
- ✅ **Giới thiệu cá nhân** với avatar và thông tin
- ✅ **Blog chia sẻ** kinh nghiệm học tập
- ✅ **Tin tức công nghệ** cập nhật
- ✅ **Tạo mã QR** miễn phí
- ✅ **Lịch học** tích hợp Google Sheets
- ✅ **Giao diện đa ngôn ngữ** (Tiếng Việt - Anh)
- ✅ **Dark/Light mode**
- ✅ **Responsive design**

## Cách thay đổi ảnh cá nhân

### Bước 1: Chuẩn bị ảnh
- Kích thước khuyến nghị: **200x200px** hoặc **400x400px**
- Định dạng: JPG, PNG, hoặc SVG
- Tên file: `avatar.jpg`, `avatar.png`, hoặc `avatar.svg`

### Bước 2: Thay thế ảnh
1. Đặt ảnh vào thư mục `images/`
2. Đổi tên thành `avatar.jpg` (hoặc định dạng tương ứng)
3. Hoặc cập nhật đường dẫn trong file `index.html`:

```html
<img src="images/your-avatar.jpg" alt="Đồng Quang Đức" class="avatar">
```

### Bước 3: Tùy chỉnh thông tin
Chỉnh sửa thông tin cá nhân trong file `index.html`:

```html
<div class="personal-info">
  <h3>Tên của bạn</h3>
  <p>Chức danh/Nghề nghiệp</p>
  <p>Mô tả ngắn</p>
  
  <div class="personal-tags">
    <span class="personal-tag">Tag 1</span>
    <span class="personal-tag">Tag 2</span>
    <span class="personal-tag">Tag 3</span>
  </div>
</div>
```

## Cấu trúc thư mục
```
/
├── index.html          # File chính
├── images/             # Thư mục ảnh
│   └── avatar.svg      # Ảnh cá nhân
└── README.md           # Hướng dẫn này
```

## Tùy chỉnh khác

### Thay đổi màu sắc
Chỉnh sửa biến CSS trong `index.html`:
```css
:root {
  --primary-color: #667eea;    /* Màu chính */
  --secondary-color: #764ba2;  /* Màu phụ */
  --accent-color: #f093fb;     /* Màu nhấn */
}
```

### Thêm tính năng mới
1. Tạo section mới trong HTML
2. Thêm CSS styling
3. Cập nhật navigation menu
4. Thêm JavaScript nếu cần

## Liên hệ
- **Facebook**: [Đồng Quang Đức](https://facebook.com/Mbbank22222006666666DQD)
- **Email**: [email của bạn]
- **GitHub**: [username của bạn]

---
*Duck Soft - Công nghệ dễ hiểu cho mọi người* 🚀