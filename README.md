# GeGe Team — WoW Forever Boosting

Trang dịch vụ boosting WoW Forever của GeGe Team (Nhà Cáo), dành cho khách quốc tế. Mở `index.html` để xem trang.

- 4 ngôn ngữ, mặc định English; chọn Tiếng Việt / Bahasa Indonesia / Filipino ở nút địa cầu.
- Danh mục 14 dịch vụ (Powerleveling, Dungeon, Profession, Raid, PvP, Mount...), mỗi dịch vụ có trang chi tiết: tùy chọn nhân vật, tốc độ, bản tóm tắt đơn để gửi qua Discord.
- Không có giá cố định: mọi đơn đều thương lượng trên Discord, thanh toán USDT theo mốc tiến độ.
- Hỗ trợ chính qua Discord: https://discord.gg/t2fPyUPGY
- Link mở thẳng một dịch vụ: `?svc=<mã dịch vụ>` (ví dụ `?svc=raid-boost`), chọn ngôn ngữ: `?lang=vi|en|id|fil`.
- `boosting/` chỉ còn là trang chuyển hướng cho link cũ.

## Sửa nội dung

Nằm trong thẻ `<script>` của `index.html`:

- `I18N`: toàn bộ chữ trên trang theo 4 ngôn ngữ.
- `PRODUCTS`: danh sách dịch vụ (ảnh, danh mục, mô tả theo ngôn ngữ). `featured: true` thì hiện ở "Top Offers".
- `DISCORD`: link Discord.

Phần trang thu mua gold cũ đã bỏ; xem lại trong lịch sử git nếu cần.
