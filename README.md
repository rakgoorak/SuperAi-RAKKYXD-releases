# SuperAi & RAKKYXD

ใช้ Claude, ChatGPT (Codex), Antigravity, OpenCode และ Freebuff ในโปรแกรมเดียว หน้าจอภาษาไทย บน Windows และ macOS ไม่ต้องเปิดหลายโปรแกรมแล้วสลับไปมา

## ดาวน์โหลด (รุ่นล่าสุด)

| เครื่อง | ดาวน์โหลด | ขนาด |
| --- | --- | --- |
| Windows 10/11 64-bit | [SuperAi-RAKKYXD-windows-x64.zip](https://github.com/rakgoorak/SuperAi-RAKKYXD-releases/releases/latest/download/SuperAi-RAKKYXD-windows-x64.zip) · [sha256](https://github.com/rakgoorak/SuperAi-RAKKYXD-releases/releases/latest/download/SuperAi-RAKKYXD-windows-x64.zip.sha256) | 133 MB |
| Mac Apple Silicon (M1 ขึ้นไป) | [SuperAi-RAKKYXD-macos-arm64.zip](https://github.com/rakgoorak/SuperAi-RAKKYXD-releases/releases/latest/download/SuperAi-RAKKYXD-macos-arm64.zip) · [sha256](https://github.com/rakgoorak/SuperAi-RAKKYXD-releases/releases/latest/download/SuperAi-RAKKYXD-macos-arm64.zip.sha256) | 114 MB |
| Mac Intel | [SuperAi-RAKKYXD-macos-x64.zip](https://github.com/rakgoorak/SuperAi-RAKKYXD-releases/releases/latest/download/SuperAi-RAKKYXD-macos-x64.zip) · [sha256](https://github.com/rakgoorak/SuperAi-RAKKYXD-releases/releases/latest/download/SuperAi-RAKKYXD-macos-x64.zip.sha256) | 120 MB |

ดูทุกรุ่นได้ที่ [Releases](https://github.com/rakgoorak/SuperAi-RAKKYXD-releases/releases/latest)

## ติดตั้ง

- **Windows:** แตก ZIP ทั้งโฟลเดอร์แล้วเปิด `SuperAi-RAKKYXD.exe` ถ้าขึ้น "Windows protected your PC" ให้กด **More info → Run anyway**
- **macOS:** แตก ZIP แล้วลาก `SuperAi-RAKKYXD.app` ไปไว้ใน Applications ถ้าเปิดไม่ได้ให้ไปที่ **System Settings → Privacy & Security → Open Anyway**

ไม่ต้องติดตั้งอะไรก่อน ครั้งแรกแอปจะเปิดหน้า **เริ่มต้นใช้งาน** ที่ตรวจเครื่องและติดตั้ง Node.js, Git และ CLI ของ AI ให้

> รุ่นนี้ยังไม่มีลายเซ็นผู้พัฒนาของ Windows หรือ Apple notarization ใช้ไฟล์ `.sha256` ตรวจว่า ZIP ไม่เสียหาย

## ความสามารถหลัก

- **3 โหมด**
  - **Agent:** Main 1 ตัววางแผนและแจกงานให้ Sub-agent 1–6 ตัวทำพร้อมกัน เห็นว่าแต่ละตัวกำลังทำอะไร
  - **Code:** เปิด CLI หลายแท็บในหน้าต่างเดียว
  - **Chat:** ถามคำถามเดียวกับ AI หลายตัว แล้วสรุปรวมว่าใครแนะนำอะไร
- **เลือก model และ effort ได้ทุกที่** และตั้งค่าเริ่มต้นของแต่ละผู้ให้บริการได้
- **Skills:** AI เสนอ skill จากแหล่งทางการของ Anthropic และ OpenAI และจะติดตั้งเมื่อคุณกดยืนยันเท่านั้น
- **อัปเดตในแอป:** ตรวจเวอร์ชันใหม่ทุกครั้งที่เปิด กดแล้วติดตั้งทับได้ทันที โดยตรวจ SHA-256 ก่อนติดตั้ง
- **อื่นๆ:** พูดเพื่อพิมพ์ภาษาไทยบนเครื่อง, แนบรูปและ PDF และ Browser Preview

## ข้อควรรู้

- เก็บโปรแกรมไว้ในโฟลเดอร์ที่คุณเขียนได้ เช่น Documents หรือ Applications เพื่อให้ปุ่มอัปเดตติดตั้งทับได้
- CLI แต่ละตัวต้องเข้าสู่ระบบด้วยบัญชีของคุณเอง ค่าใช้จ่ายและโควตาขึ้นกับผู้ให้บริการ บางรุ่นอาจใช้กับแพ็กเกจของบัญชีคุณไม่ได้
- Freebuff ใช้ได้เฉพาะโหมด Code
