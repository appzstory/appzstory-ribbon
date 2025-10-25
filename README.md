# 🖤 AppzStory Ribbon

ริบบิ้นสำหรับติดมุมเว็บไซต์ เพื่อแสดงความอาลัยอย่างสุภาพ (Simple black mourning ribbon for website corners)

โปรเจกต์นี้มีไฟล์รูปภาพริบบิ้นสำหรับแสดงความอาลัย 4 มุม (บนซ้าย, บนขวา, ล่างซ้าย, ล่างขวา) เพื่อให้คุณสามารถนำไปติดตั้งบนเว็บไซต์ได้อย่างง่ายดาย

## 📌 วิธีการใช้งาน (How to use)

คุณสามารถเลือกติดตั้งริบบิ้นในมุมใดมุมหนึ่ง (หรือหลายมุม) ได้ตามต้องการ

**ขั้นตอน:**
1.  เลือกโค้ด HTML ของมุมที่คุณต้องการ (เช่น บนซ้าย, บนขวา)
2.  คัดลอกโค้ด `<img>` ด้านล่างนี้
3.  นำไปวางไว้ในไฟล์ `index.html` (หรือไฟล์หลักของเว็บไซต์) โดยแนะนำให้วางไว้ก่อนแท็กปิด `</body>`

---

### 1. ริบบิ้นมุมบนซ้าย (Top-Left Ribbon)

```html
<img src="https://raw.githubusercontent.com/appzstory/appzstory-ribbon/main/black_ribbon_top_left.png" 
     alt="Black Ribbon Top Left" 
     style="position:fixed; top:0; left:0; width:80px; opacity:0.9; z-index:9999; pointer-events:none;">
```

---

### 2. ริบบิ้นมุมบนขวา (Top-Right Ribbon)

```html
<img src="https://raw.githubusercontent.com/appzstory/appzstory-ribbon/main/black_ribbon_top_right.png" 
     alt="Black Ribbon Top Right" 
     style="position:fixed; top:0; right:0; width:80px; opacity:0.9; z-index:9999; pointer-events:none;">
```

---

### 3. ริบบิ้นมุมล่างซ้าย (Bottom-Left Ribbon)

```html
<img src="https://raw.githubusercontent.com/appzstory/appzstory-ribbon/main/black_ribbon_bottom_left.png" 
     alt="Black Ribbon Bottom Left" 
     style="position:fixed; bottom:0; left:0; width:80px; opacity:0.9; z-index:9999; pointer-events:none;">
```

---

### 4. ริบบิ้นมุมล่างขวา (Bottom-Right Ribbon)

```html
<img src="https://raw.githubusercontent.com/appzstory/appzstory-ribbon/main/black_ribbon_bottom_right.png" 
     alt="Black Ribbon Bottom Right" 
     style="position:fixed; bottom:0; right:0; width:80px; opacity:0.9; z-index:9999; pointer-events:none;">
```

**ข้อแนะนำ:**
* `width:80px;` คุณสามารถปรับขนาดความกว้างได้ตามต้องการ
* `opacity:0.9;` คุณสามารถปรับความโปร่งใสได้ (0.0 คือโปร่งใสทั้งหมด, 1.0 คือทึบ)
* `pointer-events:none;` มีไว้เพื่อให้สามารถคลิกทะลุริบบิ้นไปยังเนื้อหาด้านหลังได้

## ✍️ Authors & Contact

* **Yothin Sapsamran** - **Initial work** - [appzstory.dev](https://appzstory.dev/)
* **FanPage:** [Facebook Fanpage](https://www.facebook.com/WebAppzStory/)
* **Youtube:** [Youtube Channel](https://www.youtube.com/appzstorystudio)
* **Line:** [@appzstory](https://lin.ee/djGJw9L)
* **Tiktok:** [@appzstory.dev](https://www.tiktok.com/@appzstory.dev)
