# Nguyen Kha - Profile + Blog (GitHub Pages)

## Chạy thử trên máy
- Mở file `index.html` bằng trình duyệt (Chrome/Edge).
- Hoặc dùng VS Code Live Server (nếu bạn có dùng).

## Deploy lên GitHub Pages (cách đơn giản)
1. Tạo repo mới trên GitHub (ví dụ: `kha-profile`).
2. Upload toàn bộ các file trong thư mục này lên repo.
3. Vào repo trên GitHub:
   - **Settings**
   - **Pages**
   - **Build and deployment**
   - **Source**: chọn **Deploy from a branch**
   - **Branch**: chọn `main` và thư mục `/root`
4. Chờ 1-2 phút, GitHub sẽ cung cấp link dạng:
   - `https://<username>.github.io/<repo>/`

## Tuỳ biến nhanh
- Sửa nội dung ở `index.html` (Profile)
- Thêm bài viết:
  - Tạo file mới trong `blog/posts/` (copy từ `bai-viet-dau-tien.html`)
  - Thêm link bài viết vào `blog/index.html`

## Gợi ý nâng cấp (nếu bạn muốn)
- Tự động hoá blog bằng Markdown + generator (Eleventy / Jekyll)
- Thêm mục Projects, CV, và liên kết GitHub/LinkedIn
