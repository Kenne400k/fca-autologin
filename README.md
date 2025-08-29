# 🌐 SPN.IO.VN – Nền tảng Giải đấu & Bảng xếp hạng Free Fire

[![Website](https://img.shields.io/badge/Website-spn.io.vn-blue?style=for-the-badge&logo=google-chrome)](https://spn.io.vn)
[![Free](https://img.shields.io/badge/chỉ%20với-300%20Đ-brightgreen?style=for-the-badge&logo=freebsd)](https://spn.io.vn)
[![Security](https://img.shields.io/badge/An%20Toàn%20%26%20Bảo%20Mật-Yes-green?style=for-the-badge&logo=lock)](https://spn.io.vn)

🔥 **[https://spn.io.vn](https://spn.io.vn)** – Website hỗ trợ **tính điểm, tạo bảng xếp hạng, và quản lý giải đấu Free Fire** một cách tự động, nhanh chóng và **hoàn toàn miễn phí**.

![Giao diện SPN.IO.VN](https://i.imgur.com/xwx1Q8M.png)

---

## ✨ Tính Năng Nổi Bật

-   🏆 **Tổ Chức Giải Đấu Chuyên Nghiệp:** Tạo và quản lý giải đấu Free Fire một cách dễ dàng.
-   📊 **Quản Lý Toàn Diện:** Hỗ trợ tạo bảng xếp hạng, line-up, boxscrim, quản lý đội hình và tạo mã QR tiện lợi.
-   🎨 **Thư Viện Layout Đa Dạng:** Kho giao diện phong phú, đẹp mắt (VIP, thường, độc quyền).
-   🔐 **An Toàn & Miễn Phí:** Nền tảng an toàn, bảo mật và miễn phí cho mọi người dùng.
-   ⚡ **Tự Động Hóa:** Tích hợp bot tính điểm tự động và hệ thống nạp tiền nhanh chóng.

👉 Nếu bạn là một nhà tổ chức giải đấu Free Fire, **[spn.io.vn](https://spn.io.vn)** là công cụ không thể thiếu.
🚀 Trải nghiệm ngay tại: **[https://spn.io.vn](https://spn.io.vn)**

---

# 🤖 FCA AutoLogin – Horizon Edition

**FCA AutoLogin** là một module mở rộng cho **FCA-HZI (Horizon Remake)**, được thiết kế để tự động hóa hoàn toàn quá trình đăng nhập Facebook, cực kỳ hữu ích khi vận hành bot Messenger 24/7.

---

## 🔑 Chức Năng Chính

-   🔄 **Tự Động Đăng Nhập:** Khi `appState` hết hạn hoặc tài khoản bị đăng xuất, bot sẽ tự động đăng nhập lại bằng email, mật khẩu và mã 2FA.
-   🛡️ **Xử Lý Checkpoint:** Tự động gửi cảnh báo khi tài khoản bị checkpoint và hỗ trợ quá trình khôi phục.
-   💾 **Tự Động Lưu `appState`:** Sau mỗi lần đăng nhập thành công, `appState` mới sẽ được tự động lưu lại để sử dụng cho các phiên tiếp theo.
-   ⚡ **Tự Động Khởi Động Lại:** Khi mất kết nối hoặc gặp lỗi, bot sẽ tự khởi động lại mà không cần can thiệp thủ công.

---

## 📂 Cấu Trúc Thư Mục Dự Án

```yaml
/filebot
├── fca/              # Thư viện FCA-HZI (Horizon)
├── lib/fblogin.js    # Module chính xử lý AutoLogin
├── index.js          # File khởi động bot
├── config.json       # File cấu hình (bao gồm bật/tắt AutoLogin)
└── appstate.json     # File appState được lưu và cập nhật tự động
