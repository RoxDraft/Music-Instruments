# Interactive Concert Grand Piano Model

เปียโนแกรนด์คอนเสิร์ตแบบ 3 มิติ เล่นได้จริง เปิดดูการทำงานภายในได้ทีละชิ้น ใช้เทียบเทคนิคการทำเปียโนของแต่ละผู้ผลิตและสไตล์ของศิลปิน และมีเปียโนไฟฟ้าวางเทียบข้างๆ

> 🤖 สร้างโดย **Claude** (Anthropic)

## ไฟล์
- `Concert Grand Studio.html`: ไฟล์หลัก
- `three-d-stage.js`: ส่วนแสดงผลและส่งออกโมเดล 3 มิติ (OBJ/GLB)
- `Concert Grand Piano (standalone).html`: ไฟล์เดียวจบ ดับเบิลคลิกเปิดได้เลย
- `.github/workflows/pages.yml`: deploy ขึ้น GitHub Pages อัตโนมัติ

## Deploy ด้วย GitHub Actions
1. Push ไฟล์ทั้งหมดขึ้น branch `main`
2. ไปที่ **Settings → Pages → Source** แล้วเลือก **GitHub Actions**
3. ทุกครั้งที่ push ระบบจะ deploy ให้ที่ `https://<username>.github.io/<repo>/`
