# Web Suite Online
Media Vault + Music Hub đã gộp thành một Node.js/Express server và một URL.
## Chạy
Node.js 18+: `npm install` rồi `npm start`, mở `http://localhost:3000`.
## Deploy online
Server mặc định `HOST=0.0.0.0`, `PORT=3000`. Đặt `JAMENDO_CLIENT_ID` trong Environment Variables. `STORAGE_DIR` và `MUSIC_DIR` nên dùng persistent disk/volume khi deploy cloud.
## Chức năng
Media Vault: upload/xem/tải/xóa ảnh video. Music Hub: tìm Jamendo, thư viện riêng, upload nhạc, tải/lưu offline. Hai giao diện chuyển bằng nút trên cùng một trang.
