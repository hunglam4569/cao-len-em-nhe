# 🚀 Hướng dẫn đưa lên GitHub Pages (Live Web)

## Bước 1 — Tạo tài khoản GitHub
Nếu chưa có: vào https://github.com → Sign up → điền email, mật khẩu, username

---

## Bước 2 — Tạo Repository mới

1. Đăng nhập GitHub → nhấn nút **"+"** góc trên phải → **"New repository"**
2. Điền thông tin:
   - **Repository name**: `cao-len-em-nhe`
   - **Description**: 🌸 Ứng dụng nhắc nhở tăng chiều cao
   - Chọn **Public** (bắt buộc để dùng GitHub Pages miễn phí)
   - ✅ Tick **"Add a README file"** → bỏ qua, mình sẽ upload file riêng
   - Nhấn **"Create repository"**

---

## Bước 3 — Upload các file lên GitHub

1. Trong trang repo vừa tạo, nhấn **"uploading an existing file"** (hoặc nút **Add file → Upload files**)
2. Kéo thả **TẤT CẢ** các file sau vào ô upload:
   - `index.html`  ← file chính (quan trọng nhất!)
   - `README.md`
   - `LICENSE`
   - `.nojekyll`   ← file ẩn, quan trọng!
3. Kéo xuống, nhấn **"Commit changes"** (màu xanh)

> ⚠️ File `.nojekyll` có thể bị ẩn trên máy Mac/Linux.
> Nếu không thấy, hãy bật "Hiện file ẩn" hoặc upload trực tiếp qua web GitHub.

---

## Bước 4 — Bật GitHub Pages

1. Vào tab **Settings** (thanh ngang trên cùng của repo)
2. Kéo xuống mục **"Pages"** (bên trái, dưới phần "Code and automation")
3. Tại **"Source"**: chọn **"Deploy from a branch"**
4. Tại **"Branch"**: chọn **main** → chọn **/ (root)** → nhấn **Save**
5. Đợi khoảng **1-3 phút** → trang sẽ hiện link dạng:
   ```
   https://[username].github.io/cao-len-em-nhe
   ```

---

## Bước 5 — Truy cập và chia sẻ 🎉

- Mở link trên trình duyệt là xong!
- Copy link gửi cho người thân dùng ngay, không cần cài gì cả 💕
- Có thể **"Add to Home Screen"** trên điện thoại để dùng như app thật

---

## ❓ Câu hỏi thường gặp

**Q: Tại sao phải đặt tên file là `index.html`?**
A: GitHub Pages tự động tìm file `index.html` làm trang chủ. Nếu đặt tên khác (như `cao-len-em-nhe.html`) sẽ báo lỗi 404.

**Q: File `.nojekyll` để làm gì?**
A: Ngăn GitHub xử lý nhầm file của mình qua Jekyll (hệ thống blog của GitHub), đảm bảo HTML hiển thị đúng.

**Q: Dữ liệu người dùng có bị mất không khi update?**
A: Không! Dữ liệu lưu trong `localStorage` của trình duyệt người dùng, không liên quan đến GitHub.

**Q: Muốn cập nhật nội dung thì làm sao?**
A: Upload lại file `index.html` mới lên GitHub → GitHub Pages tự cập nhật sau vài phút.
