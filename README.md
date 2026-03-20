# Static Website — Dịch Thuật Busan

Website tĩnh được generate tự động từ Laravel app.

## Cấu trúc
```
static_web/
├── index.html          # Trang chủ
├── images/             # Logo và ảnh local
├── storage/            # Ảnh upload từ admin
├── assets/
│   ├── cdn/            # CSS/JS từ CDN (Tailwind, Font Awesome, Alpine.js, Google Fonts)
│   ├── ext/            # Ảnh từ domain ngoài (dichthuatvantin.com)
│   └── fonts/          # Web fonts
└── README.md
```

## Deploy
- Upload toàn bộ thư mục `static_web/` lên hosting tĩnh (Netlify, Vercel, GitHub Pages, v.v.)
- Hoặc serve bằng nginx/apache trỏ root vào thư mục này

## Lưu ý
- Form liên hệ đã bị disable (static site không có server-side processing)
- Để cập nhật nội dung: chỉnh qua admin Laravel rồi chạy lại `python3 generate_static.py`
