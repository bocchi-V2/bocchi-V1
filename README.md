# bocchi 🎬
**ดาวน์โหลดวิดีโอ TikTok / Reels ไม่มีลายน้ำ — ฟรี ไม่ต้องติดตั้งอะไร**

[![Deploy to GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://YOUR-USERNAME.github.io/snapload)

## วิธี Deploy บน GitHub Pages (ฟรี)

### ขั้นตอนที่ 1 — สร้าง GitHub Repository
1. ไปที่ [github.com](https://github.com) → **Sign up** (ถ้ายังไม่มีบัญชี)
2. กด **New** (ปุ่มสีเขียว) → ตั้งชื่อ repo เช่น `snapload`
3. ตั้งเป็น **Public** → กด **Create repository**

### ขั้นตอนที่ 2 — อัปโหลดไฟล์
**วิธีง่าย (ไม่ต้องใช้ Git):**
1. ในหน้า repo ที่สร้าง → คลิก **uploading an existing file**
2. ลาก `index.html` วางลงในกล่อง
3. กด **Commit changes**

### ขั้นตอนที่ 3 — เปิด GitHub Pages
1. ไปที่ **Settings** (ในหน้า repo)
2. เมนูซ้าย → **Pages**
3. ใต้ **Source** เลือก: `Deploy from a branch`
4. Branch: **main** · Folder: **/ (root)**
5. กด **Save**
6. รอ ~1 นาที แล้วเว็บจะออนไลน์ที่: `https://YOUR-USERNAME.github.io/snapload`

---

## เทคโนโลยีที่ใช้
- **TikWM API** — ดึงลิงก์วิดีโอไม่มีลายน้ำ
- **CORS Proxy Chain** — ใช้ `allorigins.win` → `corsproxy.io` เป็น fallback
- **Tailwind CSS** — UI สวยงาม
- **Vanilla JS** — เบาไว ไม่กิน resource

## หมายเหตุ
> เว็บนี้ใช้ unofficial API เพื่อการศึกษาเท่านั้น ไม่ได้ดาวน์โหลดหรือเก็บวิดีโอไว้บนเซิร์ฟเวอร์ใดๆ
