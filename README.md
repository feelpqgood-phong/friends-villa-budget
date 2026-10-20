# Friends Villa Trip Calculator

เว็บคำนวณงบทริปพูลวิลล่า 9–10 มกราคม 2570 สำหรับแชร์ในกลุ่มเพื่อน

## Features
- เลือกจำนวนคน / รถ และแก้ราคาที่พัก V1, V2
- คำนวณค่าอาหารรวม ค่าน้ำมันรวม ต่อคันและต่อคน
- คำนวณที่นอนเสริม V1 สำหรับคนที่เกิน 12 คน
- แชร์ลิงก์พร้อมค่าที่กำหนดผ่าน URL query parameters (แต่ละคนปรับของตัวเองได้)
- ไม่มีการเก็บข้อมูลของผู้ใช้ไว้ในเซิร์ฟเวอร์

## Deploy to Cloudflare Pages
1. Cloudflare Dashboard > Workers & Pages > Create application > Pages > Connect to Git.
2. Select GitHub repository `feelpqgood-phong/friends-villa-budget`, production branch `main`.
3. Framework preset: None. Build command: leave empty. Build output directory: `/` or root folder (`.`) as accepted by UI.
4. Deploy. Cloudflare assigns a public `*.pages.dev` URL.
5. Future pushes to the production branch deploy automatically.

**Important:** The calculator is for cost estimates only; confirm 9 Jan 2027 prices, availability and conditions with the property before paying. Deposit of 3,000 THB is not a net cost if fully refunded.
