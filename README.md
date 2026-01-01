# Wedding Website - Loc & Giang
Hướng dẫn nhanh cài đặt và chạy (dành cho người không chuyên).

## Yêu cầu
- Máy có cài [VSCode](https://code.visualstudio.com/)
- Kết nối internet (để cài extension Live Server)
- (Tuỳ chọn) Tài khoản GitHub để deploy

## Chạy local (bước từng bước)
1. Mở VSCode.
2. Mở folder `wedding-site` (File -> Open Folder).
3. Cài extension "Live Server" của Ritwick Dey (Marketplace).
4. Mở `index.html`. Click phải -> **Open with Live Server**.
5. Trình duyệt sẽ mở trang tại `http://127.0.0.1:5500` (hoặc khác).

## Chỉnh sửa nhanh
- Thay ảnh: `assets/images/hero.jpg` và các `gallery*.jpg`.
- Thay ngày cưới & ngày bắt đầu yêu: chỉnh `WEDDING_DATE` và `LOVE_START_DATE` trong `assets/js/main.js`.
- Thay email gửi RSVP: sửa `youremail@example.com` thành email thật.

## Deploy lên GitHub Pages (tóm tắt)
1. Tạo repo mới trên GitHub.
2. Push toàn bộ folder `wedding-site` lên repo.
3. Vào Settings -> Pages -> Source chọn branch `main` (hoặc `gh-pages`) và thư mục `/root`.
4. Sau vài phút, trang sẽ live trên `https://<your-username>.github.io/<repo-name>/`.

