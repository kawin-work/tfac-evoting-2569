# TFAC e-Voting 2569 Landing Page

ชุดไฟล์นี้จัดเตรียมสำหรับเผยแพร่เป็นเว็บไซต์แบบ static ผ่าน GitHub Pages

## โครงสร้างไฟล์

- `index.html` หน้าเว็บหลัก
- `assets/images/` รูปภาพที่ใช้ในหน้าเว็บ ได้แก่ มาสคอต, QR Code และภาพรายชื่อผู้สมัคร
- `.nojekyll` ปิดการประมวลผล Jekyll ของ GitHub Pages
- `manifest.json` ข้อมูลกำกับไฟล์และลิงก์สำคัญ

## วิธีนำขึ้น GitHub Pages

1. สร้าง repository ใหม่ใน GitHub
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ไปไว้ที่ root ของ repository
3. ไปที่ Settings > Pages
4. เลือก Source เป็น `Deploy from a branch`
5. เลือก branch `main` และ folder `/root`
6. กด Save แล้วรอ GitHub สร้าง URL ให้

## ลิงก์สำคัญในหน้าเว็บ

- ตรวจสอบสิทธิ: https://e-voting.tfac.or.th/check
- เข้าร่วมประชุมและลงคะแนน: https://e-voting.tfac.or.th/login

## หมายเหตุ

ไฟล์นี้เป็น static HTML ไม่มี JavaScript ไม่มีแบบฟอร์ม และไม่มีการเก็บข้อมูลผู้ใช้ในตัวไฟล์