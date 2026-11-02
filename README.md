# GegeTeam — WoW Forever Gold Buying Website

Trang báo rate và làm phiếu bán Gold WoW Forever của GegeTeam (Nhà Cáo). Người chơi xem rate theo Chế độ (Normal / PvP / Roleplaying / RP-PvP) và Phe (Alliance / Horde), nhập số Gold rồi gửi phiếu cho Admin qua Zalo. Trang có thêm mục Boosting (giá thương lượng), cộng đồng và chuyển đổi VI / EN.

Mở `index.html` để xem trang.

## Sửa dữ liệu

Nằm đầu thẻ `<script>` trong `index.html`:

- `RATES[ruleset][faction]`: số USDT cho 1 Gold, `null` là "Đang cập nhật".
- `BOOSTS`: danh sách dịch vụ boosting.
- `RACES`: các tộc của từng phe, dùng cho phần chọn phe.
- `ZALO_URL`: link Zalo Admin.
