# Đỗ Tấn Minh — Blog cá nhân

Trang blog cá nhân của **Đỗ Tấn Minh** — cố vấn bất động sản dòng tiền.
Nội dung dựng từ bài tự sự *"Định vị bản thân — Thế giới bên trong"*: 7 câu hỏi soi vào
thế giới bên trong và 4 giá trị cốt lõi (sự thật, trách nhiệm, bền bỉ, tận tâm).

## Cấu trúc

```
.
├── index.html                      # Trang chủ (hero, câu chuyện, giá trị, bài viết, liên hệ)
├── styles.css                      # Toàn bộ giao diện (tông xanh lá / đất — khu vườn)
├── bai-viet/
│   └── dinh-vi-ban-than.html       # Bài viết đầy đủ
└── assets/                         # Ảnh, tài nguyên (thêm sau)
```

Đây là một trang **tĩnh thuần HTML/CSS**, không cần build, không phụ thuộc.

## Xem thử trên máy

Mở trực tiếp `index.html` bằng trình duyệt, hoặc chạy một server tĩnh:

```bash
# Python 3
python -m http.server 8000
# rồi mở http://localhost:8000
```

## Đăng lên GitHub Pages

1. Đẩy code lên một repository GitHub.
2. Vào **Settings → Pages**, chọn nhánh `main`, thư mục `/ (root)`, bấm **Save**.
3. Sau ít phút, blog sẽ chạy tại `https://<username>.github.io/<tên-repo>/`.

## Cần cập nhật

- **Thông tin liên hệ** trong `index.html` (mục `#lien-he`): số điện thoại / Zalo, email, Facebook.
- Có thể thêm ảnh chân dung vào `assets/` và chèn vào hero.

---
© Đỗ Tấn Minh
