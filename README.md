# MNP Web Prototype

Bản **prototype giao diện** trang giới thiệu công ty & sản phẩm phần mềm quản lý nhà thuốc
của **MNP PharmaTech** — dùng để xem trước, đánh giá thẩm mỹ trước khi áp dụng vào dự án thật.

## Xem thử

Mở file `index.html` trực tiếp trên trình duyệt, hoặc chạy local server:

```bash
cd mnp-web-prototype
python3 -m http.server 8000
# mở http://localhost:8000
```

## Cấu trúc

```
├── index.html              # Trang chủ một trang (one-page)
├── assets/
│   ├── css/style.css       # Toàn bộ style, responsive
│   └── js/main.js          # Header, menu mobile, animation, form demo
└── README.md
```

## Nội dung trang

- **Hero** — tiêu đề, CTA dùng thử, số liệu nổi bật, mockup giao diện phần mềm
- **Đối tác** — dải logo khách hàng
- **Giới thiệu** — về công ty MNP PharmaTech
- **Sản phẩm** — 4 sản phẩm: Pharma POS, Pharma Chain, GPP Connect, Smart Stock
- **Tính năng** — 6 tính năng nổi bật (liên thông Dược quốc gia, quản lý lô/hạn dùng…)
- **Triển khai** — quy trình 4 bước
- **Khách hàng** — đánh giá của chủ nhà thuốc
- **Liên hệ** — form đăng ký dùng thử 30 ngày
- **Footer** — thông tin công ty

## Ghi chú

- Phong cách: hiện đại, chuyên nghiệp — tông xanh navy + xanh lá dược phẩm
- Font: Be Vietnam Pro (hỗ trợ đầy đủ tiếng Việt)
- Responsive: desktop, tablet, mobile
- Đây là bản prototype tĩnh — form liên hệ chỉ demo phía client
