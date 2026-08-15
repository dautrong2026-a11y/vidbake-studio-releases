# VidBake Studio

**Trình chỉnh sửa video cho nội dung ngắn (dọc 9:16) trên Windows 10/11.**
**A short-form (vertical 9:16) video editor for Windows 10/11.**

> 🌐 **VidBake Studio là một sản phẩm của VidBake — [vidbake.com](https://vidbake.com/).**
> Ghé thăm để dùng thêm nhiều công cụ khác.
> **A VidBake product — [vidbake.com](https://vidbake.com/). Visit for more tools.**

---

## 🇻🇳 Tiếng Việt

Không cần cài Python hay FFmpeg riêng — mọi thứ đã đóng gói sẵn trong bộ cài.

**Tải bản mới nhất:** vào tab [**Releases**](https://github.com/dautrong2026-a11y/vidbake-studio-releases/releases).

- **`VidBakeStudio-1.0.0-setup.exe`** — bấm 1 lần để cài (per-user, **không cần quyền admin**).
- Sau khi tải, nên kiểm chứng file bằng SHA-256 trong `checksums.txt`:
  ```powershell
  Get-FileHash -Algorithm SHA256 .\VidBakeStudio-1.0.0-setup.exe
  ```
- Nếu Windows hiện *"Windows protected your PC"* → **More info → Run anyway** (app mới chưa ký số nên bình thường).

**Tính năng chính:** cắt bằng dao + chọn nhiều clip trên timeline · hàng đợi xuất hàng loạt (lưu được khi tắt/mở lại) · xuất dọc 9:16 với nền làm mờ · tăng tốc phần cứng NVENC/QSV · giao diện **Anh/Việt**.

## 🇬🇧 English

No separate Python or FFmpeg installation required — everything is bundled in the installer.

**Download the latest build:** open the [**Releases**](https://github.com/dautrong2026-a11y/vidbake-studio-releases/releases) tab.

- **`VidBakeStudio-1.0.0-setup.exe`** — one-click install (per-user, **no admin required**).
- After downloading, verify the file against the SHA-256 in `checksums.txt`:
  ```powershell
  Get-FileHash -Algorithm SHA256 .\VidBakeStudio-1.0.0-setup.exe
  ```
- If Windows shows *"Windows protected your PC"* → **More info → Run anyway** (normal for a new, unsigned app).

**Key features:** blade cut + multi-select timeline · batch export queue (persists across restarts) · vertical 9:16 export with blur-fill background · NVENC/QSV hardware acceleration · **English/Vietnamese** UI.

---

© 2026 VidBake · [vidbake.com](https://vidbake.com/). Phần mềm sử dụng / This software
uses FFmpeg, Qt (PySide6), MediaPipe, và các thư viện mã nguồn mở khác — xem
`THIRD-PARTY-NOTICES` kèm trong bộ cài / see `THIRD-PARTY-NOTICES` bundled with the installer.
