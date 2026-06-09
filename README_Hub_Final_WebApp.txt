Hub Final Tracking Dashboard Web App Setup

ไฟล์ในชุดนี้:
1) Code.gs        = Apps Script ฝั่ง Server + API + Auto Fill Menu
2) index.html     = หน้า Web App หลัก
3) style.html     = CSS ธีม Dashboard เหมือน Sheet ที่แนบ
4) script.html    = JavaScript ฝั่งหน้าเว็บ

วิธีติดตั้ง:
1. เปิด Google Sheet: Hub Final Tracking Dashboard - Google Sheet Template
2. ไปที่ Extensions > Apps Script
3. สร้างไฟล์ตามชื่อด้านบน แล้ววางโค้ดให้ตรงไฟล์
4. กด Save
5. Reload Google Sheet จะเห็นเมนู ⚡ Auto Fill
6. เปิด Apps Script > Deploy > New deployment
7. เลือก Type = Web app
8. Execute as = Me
9. Who has access = Anyone with the link หรือภายในองค์กร
10. กด Deploy แล้วนำ Web App URL ไปเปิดใช้งาน

หมายเหตุ:
- CONFIG.SPREADSHEET_ID ใน Code.gs ใส่ ID ของชีทที่สร้างไว้ให้แล้ว
- ถ้าคัดลอกชีทไปไฟล์ใหม่ ให้เปลี่ยน SPREADSHEET_ID ตามไฟล์ใหม่
- Dropdown แก้ได้ในชีท Dropdown_Master แล้วเมนู Re-Apply Dropdown + Color จะดึงค่าใหม่ไปใช้
