# 🚀 TEMPLATE CẤU TRÚC DỰ ÁN MỚI
> *Copy file này vào bất kỳ dự án mới nào để thiết lập quy chuẩn ngay lập tức.*

## 1. Kết Nối DataHub
Dự án này sử dụng trung tâm dữ liệu tập trung **DataHub**:
- **Dữ liệu công khai**: Lấy từ `https://raw.githubusercontent.com/FatKen13/DataHub-Public/main/api/v1/...`
- **Dữ liệu cá nhân**: Đọc/ghi qua GitHub PAT vào repo `FatKen13/DataHub-Private`
- **Tài liệu kiến trúc đầy đủ**: Tham khảo tại [FatKen13 Architecture](https://github.com/FatKen13/FatKen13/blob/main/docs/ARCHITECTURE.md)

## 2. Cấu Trúc Thư Mục Tiêu Chuẩn
```text
ProjectName/
├── index.html        # Giao diện chính (HTML5 Semantic)
├── style.css         # Design System (Glassmorphism, Dark/Light)
├── manifest.json     # Cấu hình PWA Web App
├── sw.js             # Service Worker chạy Offline
├── js/
│   ├── app.js        # Controller chính
│   └── datahub.js    # Module gọi DataHub API
└── ARCHITECTURE.md   # Bản sao tài liệu kiến trúc
```
