# LocalTS AutoBuy

Tool Windows tự **săn và mua acc trên localts.store** khi có hàng, lấy acc về và **gửi thẳng vào Discord**, kèm **kho nick** để quản lý và bán lại.

© **Gia Bảo** · Discord: **Mew Mew**

## ⬇️ Tải về

Vào mục **[Releases](../../releases/latest)** → tải **`LocalTS-AutoBuy-v….zip`** (nhẹ hơn) hoặc **`LocalTS-AutoBuy.exe`**.

Chỉ cần 1 file exe, không phải cài gì thêm.

## Tính năng

- Nhập API key localts → hiện toàn bộ sản phẩm, tồn kho, giá, số dư.
- **Auto mua theo số lượng** cho từng sản phẩm:
  - *Mua dần cho đủ*: có hàng là mua liền, thiếu thì đợi mua tiếp tới đủ.
  - *Đợi đủ hàng, mua 1 lần*: chỉ mua khi kho đủ số lượng (ăn giảm giá theo số lượng).
- Kiểm tra hàng mỗi 1–2 giây, có hàng là đặt đơn ngay; nhiều sản phẩm mua cùng lúc.
- Tự lấy acc khi shop giao xong, **gửi Discord** (webhook hoặc bot nhắn riêng).
- Xử lý shop hoàn tiền / hoàn acc lỗi (tự mua bù), hết số dư, bị người khác giành hàng.
- **Kho nick**: mỗi nick 1 dòng, lọc theo danh mục/sản phẩm, phân trang, copy, **tải .txt**, đánh dấu đã bán, tự xóa nick đã bán sau 24h.
- File shop trả **gộp nhiều nick** được tự tách mỗi dòng 1 nick; mỗi nick lưu 1 file `.txt` theo thư mục danh mục.

## Cách dùng

1. Giải nén, mở `LocalTS-AutoBuy.exe`.
2. **Cài đặt** → dán API key (lấy ở localts.store → Settings) → **Lưu & kiểm tra kết nối**.
3. (Tuỳ chọn) dán **Discord Webhook URL** → **Lưu & gửi tin thử**.
4. Tab **Sản phẩm** → bấm **Auto mua khi có hàng** / **Mua ngay** → chọn số lượng → bắt đầu.
5. Nick mua về nằm ở tab **Kho nick**.

## Lưu ý

- Cần **Windows** có **Microsoft Edge hoặc Google Chrome** (app mở giao diện bằng trình duyệt).
- Lần đầu mở, Windows có thể hiện *"Windows protected your PC"* vì file chưa ký số → bấm **More info → Run anyway**.
- Dữ liệu của bạn (API key, nick đã mua) lưu ở thư mục `data` cạnh file exe. **Đừng gửi thư mục này cho ai.**
- Nếu app báo *Cloudflare chặn mạng (IP)*: mạng của bạn đang bị localts.store chặn — thử mở localts.store bằng trình duyệt; bị chặn thì đổi mạng hoặc hỏi admin shop.
