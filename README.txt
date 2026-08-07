JAIDEE โปรแกรมคำนวณดวงสติ๊กเกอร์ — ชุดเว็บไซต์พร้อมอัปโหลด

ไฟล์สำคัญ
- index.html                หน้าหลัก
- manifest.webmanifest     ตั้งค่าให้เว็บไซต์แสดงเหมือนแอป/PWA
- sw.js                    ทำให้เปิดซ้ำได้เร็วและรองรับ cache พื้นฐาน
- assets/                  ไอคอนเว็บไซต์และไอคอนบนมือถือ
- netlify.toml             ตั้งค่า Netlify
- .nojekyll                ช่วยให้ GitHub Pages เสิร์ฟไฟล์ตรง ๆ

อัปโหลด Netlify
1) แตก ZIP
2) เข้า Netlify > Add new site > Deploy manually
3) ลากทั้งโฟลเดอร์ sticker-calculator-site หรือไฟล์ทั้งหมดด้านในไปวาง
4) Netlify จะสร้างลิงก์เว็บให้ทันที

อัปโหลด GitHub Pages
1) สร้าง Repository ใหม่
2) อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ไว้ที่ root ของ repository
3) ไป Settings > Pages
4) Source: Deploy from a branch
5) เลือก branch main และ /(root) แล้ว Save

การติดตั้งเหมือนแอป
- Android/Chrome: เปิดเว็บ > เมนู > Add to Home screen / Install app
- iPhone/iPad/Safari: เปิดเว็บ > Share > Add to Home Screen
- PC Chrome/Edge: เปิดเว็บ แล้วเลือก Install app จากแถบที่อยู่/เมนู

หมายเหตุ
- ค่าเริ่มต้นพื้นที่พิมพ์ 30.2 × 44.4 ซม.
- ค่าเริ่มต้นขอบปลอดภัย 0.3 ซม. และแก้ไขได้
- สี่เหลี่ยมธรรมดาระยะห่าง 0 มม.
- ขอบมน/วงกลม/วงรีระยะห่าง 1 มม.
