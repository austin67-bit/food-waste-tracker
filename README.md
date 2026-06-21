# Food Waste Tracker — PWA

## วิธี deploy บน GitHub Pages (ฟรี 100%)

### ขั้นตอนที่ 1 — สร้าง GitHub Account
1. ไปที่ https://github.com แล้ว Sign up
2. ยืนยัน email

### ขั้นตอนที่ 2 — สร้าง Repository
1. กด **New** (ปุ่มสีเขียวมุมบนซ้าย)
2. Repository name: `food-waste-tracker` (พิมพ์ตรงๆ)
3. ติ๊ก **Public**
4. กด **Create repository**

### ขั้นตอนที่ 3 — อัปโหลดไฟล์
1. ในหน้า repository กด **uploading an existing file**
2. ลาก **ทุกไฟล์** ในโฟลเดอร์นี้ขึ้นไป (รวมโฟลเดอร์ icons/)
   - index.html
   - manifest.json
   - sw.js
   - icons/icon-192.png
   - icons/icon-512.png
3. เลื่อนลงกด **Commit changes**

### ขั้นตอนที่ 4 — เปิด GitHub Pages
1. คลิก **Settings** (แถบเมนูบน)
2. เลื่อนลงหา **Pages** (เมนูซ้าย)
3. Source → เลือก **Deploy from a branch**
4. Branch → เลือก **main** → โฟลเดอร์ **/ (root)**
5. กด **Save**
6. รอ 1-2 นาที แล้ว URL จะปรากฏ เช่น
   `https://yourname.github.io/food-waste-tracker`

### ขั้นตอนที่ 5 — แชร์ให้เพื่อน
ส่ง URL ให้เพื่อนเปิดในมือถือได้เลย!

---

## วิธีติดตั้งลงมือถือ

### iPhone / iPad (iOS)
1. เปิด Safari แล้วไปที่ URL
2. แตะปุ่ม **Share** (กล่องมีลูกศรขึ้น) ด้านล่างกลาง
3. เลื่อนหา **Add to Home Screen**
4. แตะ **Add** มุมขวาบน
5. ไอคอนแอปจะปรากฏบนหน้าจอ ✅

### Android
1. เปิด Chrome แล้วไปที่ URL
2. แตะ **⋮** (สามจุด) มุมขวาบน
3. แตะ **Add to Home Screen**
4. แตะ **Add**
5. ไอคอนแอปจะปรากฏบนหน้าจอ ✅

---

## ฟีเจอร์
- บันทึกน้ำหนักเศษอาหาร 4 แหล่งต่อวัน
- คำนวณน้ำหนักสุทธิ (หักถังเปล่า 1 kg) อัตโนมัติ
- ดูกราฟเปรียบเทียบรายวัน
- แก้ไข / ลบข้อมูลได้
- ใช้ออฟไลน์ได้ (หลัง load ครั้งแรก)
- บันทึกข้อมูลในเครื่องแต่ละคน
