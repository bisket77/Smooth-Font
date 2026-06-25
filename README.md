# ✨ Smooth Font & Smooth Scrolling ใน VS Code

เพิ่มความลื่นไหลให้การพิมพ์และการเลื่อนหน้าจอใน VS Code
## 🛠️ ขั้นตอนที่ 1 : เปิด User Settings (JSON)
1. กด **F1**
2. พิมพ์
```md
Open User Settings (JSON)
````
3. กด Enter

![Open User Settings JSON](https://github.com/user-attachments/assets/e20af860-a39a-4b2d-9ff2-dc77040e75bb)

---

## ⚙️ ขั้นตอนที่ 2 : เพิ่มโค้ดสำหรับ Smooth Font

นำโค้ดด้านล่างไปวางในไฟล์ `settings.json`

```json
{
  "editor.smoothScrolling": true,
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 2,
  "workbench.list.smoothScrolling": true,
  "terminal.integrated.smoothScrolling": true
}
```

---

## ✅ ผลลัพธ์

* เลื่อนหน้าจอได้ลื่นขึ้น
* Cursor เคลื่อนไหวแบบ Smooth
* การเลื่อนใน Explorer ลื่นขึ้น
* Terminal Scroll ได้ลื่นขึ้น
* ประสบการณ์การเขียนโค้ดดูสบายตามากขึ้น

![Smooth Font Example](https://github.com/user-attachments/assets/7d6c8634-ea49-4a2e-a262-be59f9fc4432)

---

## 🎉 เสร็จเรียบร้อย

หลังจากบันทึกไฟล์ `settings.json` การตั้งค่าจะถูกใช้งานทันที โดยไม่ต้องรีสตาร์ท VS Code

```
วิธีนี้ทำให้การเขียนโค้ดสบายตาขึ้น
```
