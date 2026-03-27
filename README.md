# DELE Membership Registration Site

เว็บไซต์สมัครสมาชิกสำหรับสมาคมการศึกษาดิจิทัลและวิศวกรรมการเรียนรู้ (DELE Thailand)

## โครงสร้างไฟล์
- `index.html` หน้าเว็บหลัก
- `assets/` เก็บรูปและไฟล์ประกอบ
- `.nojekyll` ใช้กับ GitHub Pages

## การตั้งค่า
แก้ค่า `SCRIPT_URL` ใน `index.html` ให้เป็น Google Apps Script Web App URL จริง

## การเผยแพร่ผ่าน GitHub Pages
1. อัปโหลดไฟล์ทั้งหมดขึ้น GitHub repository
2. ไปที่ Settings
3. เลือก Pages
4. Source: Deploy from a branch
5. Branch: `main`
6. Folder: `/ (root)`
7. Save

## หมายเหตุ
- อย่าใส่ข้อมูลลับลงใน `index.html`
- ระบบ backend ใช้ Google Apps Script แยกจาก GitHub Pages
Last updated
