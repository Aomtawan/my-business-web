# my-business-web

**ชื่อโปรเจค:** ไก่ทอดซาเล้ง — เว็บไซต์แสดงข้อมูลธุรกิจไก่ทอด  
**คำอธิบาย:** เว็บตัวอย่างสำหรับการบ้าน/assignment ประกอบด้วย 4 หน้า: หน้าแรก (index.html), เกี่ยวกับ (about.html), บริการ (services.html) และ ติดต่อ (contact.html) โดยใช้ semantic HTML, meta tags, และฟอร์มที่มี client-side validation

## โครงสร้างไฟล์
my-business-web
├── index.html
├── about.html
├── services.html
├── contact.html
├── images/
│ ├── logo.png
│ ├── team-member-1.jpg
│ └── ...
└── README.md


## รูปหน้าจอ
(ใส่รูปหน้าจอที่ capture มาในโฟลเดอร์ images หรือแนบไว้ใน README โดยใช้ markdown image syntax)
- ![หน้าแรก](images/screenshot-index.png)
- ![เกี่ยวกับ](images/screenshot-about.png)
- ![บริการ](images/screenshot-services.png)
- ![ติดต่อ](images/screenshot-contact.png)

## ลิงก์ไปยังแต่ละหน้า (ใน repo นี้)
- หน้าแรก: `index.html`
- เกี่ยวกับ: `about.html`
- บริการ: `services.html`
- ติดต่อ: `contact.html`

## วิธีใช้ / คำสั่ง Git (ตัวอย่าง)
```bash
# สร้าง repo ใหม่บนเครื่อง
git init
git add .
git commit -m "Initial commit - project scaffold"

# สร้าง repo บน GitHub ชื่อ my-business-web จากเว็บ github.com (หรือใช้ gh cli)
# สมมติ remote URL คือ git@github.com:USERNAME/my-business-web.git
git remote add origin git@github.com:USERNAME/my-business-web.git
git branch -M main
git push -u origin main
