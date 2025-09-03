# 🚀 NamDevTeams - Hệ Thống Team Chuyên Nghiệp

![Java](https://img.shields.io/badge/Java-17-orange.svg)
![API](https://img.shields.io/badge/API-1.20+-red.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

**NamDevTeams** là một plugin hệ thống team toàn diện, mạnh mẽ và có khả năng tùy biến cao được thiết kế cho các server Minecraft 1.20+. Với mục tiêu mang lại trải nghiệm chơi game đồng đội đỉnh cao, plugin cung cấp đầy đủ các công cụ quản lý chuyên nghiệp, giao diện trực quan và các tính năng nâng cao giúp gắn kết cộng đồng của bạn.

---

## ✨ Tính Năng Nổi Bật

<p align="center">
  <img src="https://i.imgur.com/your-panel-image.png" width="70%">
  <br>
  <em>Giao diện quản lý team trực quan và dễ sử dụng.</em>
</p>

✔️ **Quản Lý Team & Phân Quyền:**
- **Tạo, giải tán, mời, kick** thành viên.
- **Phân quyền chi tiết:** Owner (Chủ), Moderator (Phó), Member (Thành viên). Chỉ Owner/Mod mới có thể chỉnh sửa cài đặt.
- **Hệ thống Lời mời:** Quản lý lời mời tham gia team an toàn.

✔️ **Giao diện GUI Trực quan:**
- **Panel Điều khiển (`/team panel`):** Một trung tâm để truy cập mọi tính năng.
- **Quản lý Thành viên:** Xem danh sách, vai trò, trạng thái online và quản lý thành viên ngay trong GUI.
- **Cài đặt Team:** Dễ dàng bật/tắt PvP, đổi prefix team...
- **Xác nhận hành động:** Các hành động nguy hiểm như giải tán, kick đều có màn hình xác nhận để tránh nhầm lẫn.

✔️ **Tính năng Nâng cao:**
- **Team Chat (`/team chat`):** Kênh chat riêng tư, bảo mật chỉ dành cho các thành viên trong team.
- **Hệ thống Home (`/team sethome, /home`):** Đặt một điểm tập kết chung cho team với thời gian chờ dịch chuyển 5 giây để chống lạm dụng.
- **Hệ thống Đồng minh (`/team ally`):** Xây dựng liên minh chiến lược với các team khác.

✔️ **Tùy chỉnh & Tích hợp:**
- **Tùy biến 100%:** Chỉnh sửa mọi tin nhắn, tiền tố, định dạng trong `config.yml`.
- **Hỗ trợ Hex Color:** Sử dụng màu sắc hiện đại với cú pháp `&#RRGGBB;`.
- **PlaceholderAPI:** Tích hợp sẵn với các placeholder như `%namdevteams_name%` và `%namdevteams_prefix%`.
- **Hỗ trợ Folia:** Tối ưu hóa để hoạt động mượt mà trên các nền tảng server hiện đại.

---

## 🚀 Cài Đặt

1.  Tải file `NamDevTeams-1.0.0.jar` từ trang [Releases](https://github.com/your-username/your-repo/releases).
2.  Thả file `.jar` vào thư mục `/plugins/` của server Minecraft (1.20+).
3.  (Tùy chọn) Cài đặt [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/) để sử dụng các placeholder.
4.  Khởi động lại server. Plugin sẽ tự tạo các file cấu hình cần thiết.
5.  Mở file `plugins/NamDevTeams/config.yml` và tùy chỉnh theo ý muốn của bạn!

---

## 📘 Lệnh & Quyền Hạn

| Lệnh | Mô tả | Quyền hạn (Permission) |
| :--- | :--- | :--- |
| `/team create <tên>` | Tạo một team mới. | `namdevteams.user.create` |
| `/team invite <tên>` | Mời người chơi vào team. | `namdevteams.moderator.invite` |
| `/team join <tên>` | Chấp nhận lời mời. | `namdevteams.user.join` |
| `/team leave` | Rời khỏi team hiện tại. | `namdevteams.user.leave` |
| `/team kick <tên>` | Kick một thành viên. | `namdevteams.moderator.kick` |
| `/team disband` | Giải tán team. | `namdevteams.owner.disband` |
| `/team panel` | Mở bảng điều khiển team. | `namdevteams.user.panel` |
| `/team chat` | Bật/tắt chế độ chat team. | `namdevteams.user.chat` |
| `/team sethome` | Đặt home cho team. | `namdevteams.moderator.sethome` |
| `/team home` | Dịch chuyển về home team. | `namdevteams.user.home` |
| `/team delhome` | Xóa home của team. | `namdevteams.moderator.delhome` |
| `/team ally <...>` | Quản lý đồng minh. | `namdevteams.moderator.ally` |
| `/team promote <tên>`| Thăng cấp thành viên. | `namdevteams.owner.promote` |
| `/team demote <tên>` | Hạ cấp phó team. | `namdevteams.owner.demote` |
| `/team prefix <...>` | Đổi prefix của team. | `namdevteams.owner.prefix` |
| `/team reload` | Tải lại plugin. | `namdevteams.admin.reload` |

---

## 💡 Placeholders (PlaceholderAPI)

Sử dụng các placeholder sau với các plugin khác:

| Placeholder | Mô tả |
| :--- | :--- |
| `%namdevteams_name%` | Hiển thị tên team của người chơi. |
| `%namdevteams_prefix%` | Hiển thị prefix của team của người chơi (đã có màu). |

---

## ❤️ Hỗ Trợ & Đóng Góp

-   Nếu bạn phát hiện lỗi hoặc có ý tưởng mới, hãy tạo một **Issue** [tại đây](https://github.com/your-username/your-repo/issues).
-   Mọi sự đóng góp để cải thiện plugin đều được chào đón!
