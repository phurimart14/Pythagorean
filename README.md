# Pythagorean

เกมการเรียนรู้ทฤษฎีบทพีทาโกรัสแบบโต้ตอบ รองรับภาษาไทย

## ใช้งาน

เปิด `index.html` ในเบราว์เซอร์ หรือให้บริการโฟลเดอร์นี้ด้วย static web server

หน้าเว็บใช้ Tailwind CSS และ Google Fonts ผ่าน CDN จึงต้องเชื่อมต่ออินเทอร์เน็ตเพื่อโหลดรูปแบบและฟอนต์

## Deploy บน Vercel

1. Import repository `phurimart14/Pythagorean`
2. เลือก Framework Preset เป็น `Other`
3. ใช้ Root Directory เป็นรากของ repository (`./`)
4. ไม่ต้องตั้ง Build Command และใช้ Output Directory เป็น `.`
5. กด Deploy

ไฟล์ `index.html` เป็นหน้าแรกของเว็บไซต์ ไม่ต้องติดตั้ง dependencies หรือ build
