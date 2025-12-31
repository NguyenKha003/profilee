# Nguyen Kha - Profile + Blog (Java & JavaScript)

Website profile + blog cá nhân (tiếng Việt) phục vụ đồ án: chia sẻ kiến thức lập trình, tập trung chủ đề **Java** và **JavaScript**.

## Demo (GitHub Pages)
- **Live site**: https://nguyenkha003.github.io/profilee/
- **Repo**: https://github.com/NguyenKha003/profilee

## Yêu cầu đồ án (tóm tắt)
- Có trang **Home** và trang **Blog** (menu điều hướng).
- Nội dung blog: tối thiểu **9 bài post** tiếng Việt về chủ đề **Java & JavaScript**.
- Trình bày tối giản, dễ đọc.
- Kỹ thuật: sử dụng **GitHub Repo** (commit history, branch/PR, issue nếu có) + deploy GitHub Pages.

## Cấu trúc thư mục
- `index.html`: Home/Profile
- `about.html`, `contact.html`: các trang phụ (Skills nằm ở `contact.html`)
- `styles.css`, `home.css`: giao diện
- `blog/index.html`: danh sách bài viết
- `blog/posts/*.html`: bài viết

## Chạy thử trên máy
- Mở file `index.html` bằng trình duyệt (Chrome/Edge).
- Hoặc dùng VS Code Live Server.

## Quy trình GitHub Repo (đúng kỹ thuật)

### 1) Làm việc theo nhánh (branch)
Mỗi thay đổi nên làm trên 1 nhánh riêng, sau đó tạo Pull Request vào `main`.

Ví dụ tên nhánh:
- `feature/add-post-java-basics`
- `feature/improve-blog-index`
- `fix/nav-links`

Lệnh mẫu:
```bash
git checkout -b feature/add-post-java-basics
git add .
git commit -m "feat: add Java basics post"
git push -u origin feature/add-post-java-basics
```

### 2) Quy ước commit message
- `feat:` thêm tính năng/bài viết
- `fix:` sửa lỗi
- `refactor:` chỉnh code không đổi chức năng
- `docs:` chỉnh README/nội dung mô tả

Ví dụ:
- `feat: add 5 new Java/JavaScript posts`
- `fix: update blog links and titles`

### 3) Pull Request (PR)
- Tạo PR từ branch → `main`
- Mô tả ngắn: đã làm gì, ảnh chụp (nếu có)
- Merge khi ổn

### 4) Issues (minh chứng quản lý công việc)
Bạn có thể tạo Issues trên GitHub để chứng minh quản lý task.

Gợi ý issues:
- [ ] Add 9 Java/JavaScript posts
- [ ] Update blog index UI
- [ ] Fix header responsive
- [ ] Deploy GitHub Pages

## Deploy GitHub Pages
Repo → **Settings** → **Pages**:
- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/(root)`

## Thêm bài viết mới
1. Tạo file mới trong `blog/posts/` (copy từ một bài có sẵn).
2. Sửa `title`, `meta description`, `h1`, nội dung.
3. Thêm link vào `blog/index.html`.
