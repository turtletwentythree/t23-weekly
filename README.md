# T23 Weekly: Project Tracking Dashboard

โค้ดหน้า Dashboard ของ Turtle 23 ที่สรุปข้อมูลจากไฟล์ Project Tracking.xlsx (T23 Management Weekly)

## มีอะไรใน repo นี้

- `index.html` คือโค้ดหน้า Dashboard ทั้งหมด (HTML, CSS, JavaScript)

repo นี้ไม่มีข้อมูลโปรเจกต์ ไม่มีไฟล์ Excel และไม่มีโลโก้

## หน้า Dashboard แสดงอะไร

- **Project Update:** ตัวเลขสรุป กราฟตามสถานะและ Priority กราฟ Priority per project และตารางโปรเจกต์
- **Operation:** ตารางบันทึกของแต่ละร้านแยกตามแผนก
- **Sync data:** ปุ่มอ่านไฟล์ Project Tracking.xlsx ใหม่

## ข้อจำกัด

- โค้ดนี้ทำงานเฉพาะบน claude.ai ในรูปแบบ Dashboard เพราะใช้ระบบของ claude.ai อ่านข้อมูลผ่านตัวเชื่อม Microsoft 365 ถ้าเปิดไฟล์นี้ตรง ๆ ในเบราว์เซอร์หรือ GitHub Pages จะไม่แสดงข้อมูล
- รูปโลโก้ในหน้าอ้างถึงไฟล์ภายใน claude.ai จึงไม่แสดงเมื่อเปิดนอก claude.ai
- ถ้าต้องการให้ใช้งานนอก claude.ai ต้องปรับโค้ดส่วนอ่านข้อมูลเพิ่ม

## วิธีอ่านข้อมูลจากไฟล์

- Progress แสดง 4 อัพเดทล่าสุด และ Action Plan รวม Action Plan กับ Action 2 แล้วแสดง 4 รายการล่าสุด (ข้อความในไฟล์ไม่มีวันที่ จึงตัดตามจำนวนรายการ ไม่ใช่ตามวัน)
- ตารางเรียงตาม Priority โดยสถานะ TBC อยู่ล่างสุด
