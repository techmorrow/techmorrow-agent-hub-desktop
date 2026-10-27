# Agent Hub Desktop

แอปเดสก์ท็อปของ [Agent Hub](https://admin.jetdigital.studio/app/) สำหรับ macOS และ Windows
repo นี้ใช้แจกไฟล์ติดตั้งและอัปเดตอัตโนมัติเท่านั้น (ซอร์สโค้ดอยู่ใน repo หลักของ Agent Hub)

## ดาวน์โหลดเวอร์ชันล่าสุด

- Mac ชิป Apple (M1 ขึ้นไป): [Agent-Hub-mac-arm64.dmg](https://github.com/techmorrow/techmorrow-agent-hub-desktop/releases/latest/download/Agent-Hub-mac-arm64.dmg)
- Mac Intel: [Agent-Hub-mac-x64.dmg](https://github.com/techmorrow/techmorrow-agent-hub-desktop/releases/latest/download/Agent-Hub-mac-x64.dmg)
- Windows 10/11: [Agent-Hub-Setup.exe](https://github.com/techmorrow/techmorrow-agent-hub-desktop/releases/latest/download/Agent-Hub-Setup.exe)

## เปิดครั้งแรก

แอปยังไม่ได้ลงลายเซ็นนักพัฒนา จึงมีคำเตือนครั้งแรก

- **macOS:** ลาก Agent Hub ไปไว้ใน Applications แล้วคลิกขวา → Open → Open
  (หรือ System Settings → Privacy & Security → Open Anyway) ถ้าขึ้นว่าไฟล์เสีย ให้รัน
  `xattr -cr "/Applications/Agent Hub.app"` ใน Terminal
- **Windows:** ถ้าขึ้น "Windows protected your PC" ให้กด More info → Run anyway
