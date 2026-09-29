# HOANGGIA — PROMPT NỘI THẤT

Công cụ tạo prompt chuyên nghiệp cho hình ảnh nội thất và kiến trúc.

## Cấu trúc

```text
HOANGGIA-PROMPT-NOI-THAT/
├── index.html
├── README.md
├── LICENSE
└── assets/
```

## Chạy trên máy

Chỉ cần mở trực tiếp file `index.html` bằng trình duyệt.

Không cần:
- Node.js
- npm
- React
- Vite
- cơ sở dữ liệu
- máy chủ

## Đưa lên GitHub Pages

### Cách 1 — Upload trực tiếp trên GitHub

1. Tạo một repository mới trên GitHub.
2. Có thể đặt tên: `hoanggia-prompt-noi-that`.
3. Chọn **Public**.
4. Tải toàn bộ nội dung thư mục này lên repository.
5. Đảm bảo `index.html` nằm ở thư mục gốc của repository.
6. Vào:

**Settings → Pages**

7. Ở **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
8. Nhấn **Save**.
9. Chờ GitHub Pages triển khai.
10. Trang sẽ có dạng:

```text
https://TEN-GITHUB-CUA-BAN.github.io/hoanggia-prompt-noi-that/
```

## Lưu ý

Phiên bản hiện tại là frontend thuần HTML/CSS/JavaScript và sử dụng bộ luật tạo prompt cục bộ. Chưa kết nối API AI hoặc hệ thống phân tích hình ảnh thực sự.

Có thể phát triển tiếp thành phiên bản V2 với:
- tải ảnh căn phòng
- phân tích không gian bằng AI
- nhận diện vật liệu
- nhận diện ánh sáng
- phân tích bố cục
- đạo diễn góc máy
- đề xuất tiêu cự
- đề xuất độ cao camera
- lựa chọn góc kể chuyện
- tạo prompt riêng cho Lovart
- tạo prompt cho ChatGPT Image
- tạo prompt cho Midjourney
- khóa bố cục khi image-to-image
