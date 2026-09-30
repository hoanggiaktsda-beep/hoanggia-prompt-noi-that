# HOANGGIA AI Studio

**Architecture × Interior × Artificial Intelligence**

Creative workspace AI định hướng cho kiến trúc sư, nhà thiết kế nội thất và visual artists. Repo này phát triển trực tiếp từ HOANGGIA Prompt Nội Thất.

## Studio Modules

- Interior Director
- Image Director
- Camera Director
- Material Lab
- Lighting Lab
- Prompt Library
- AI Backend (API-ready)

## Product principle

**SEE → UNDERSTAND → DIRECT → GENERATE**

HOANGGIA AI Studio không chỉ viết prompt; mục tiêu là trở thành creative operating system cho workflow kiến trúc và nội thất.

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

Phiên bản hiện tại là frontend thuần HTML/CSS/JavaScript với Prompt Engine cục bộ. Đã có giao diện Studio, module navigation, reference-image preview, camera/lighting controls, prompt generation, copy/export. Chưa kết nối AI Vision/Image Generation backend.

Lộ trình V3 backend:
- AI Vision phân tích ảnh
- Image generation / editing
- Preserve architecture / furniture
- Project history
- Prompt Library
- Authentication / storage
- AI provider routing

Có thể phát triển tiếp với:
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
