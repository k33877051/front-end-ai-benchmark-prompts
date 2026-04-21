# 🧪 Front-End AI Benchmark Prompts (HTML, CSS, JavaScript)

ชุด Prompt สำหรับทดสอบความสามารถของ AI ด้าน Front-End  
ใช้วัดว่า AI สามารถสร้าง UI, เขียนโค้ด, จัดการ Logic และทำงานระดับ Production ได้ดีแค่ไหน

---

## 🎯 เป้าหมายของ Repository นี้

- ทดสอบความสามารถ AI ในการพัฒนา Front-End
- เปรียบเทียบ AI หลายตัว (เช่น GPT, Claude, Copilot)
- วัดคุณภาพโค้ด ไม่ใช่แค่ “ทำงานได้”
- ใช้เป็นเครื่องมือฝึก Dev / Content / Course

---

## 🧠 สิ่งที่ควรดูเวลา Test AI

อย่าดูแค่ว่า “มันทำได้ไหม”  
ให้ดูด้วยว่า:

- HTML semantic ถูกต้องไหม
- CSS เป็นระบบไหม (layout / spacing / responsive)
- JavaScript แยก logic ดีไหม
- UX ใช้งานได้จริงไหม
- มี validation / edge cases หรือไม่
- โค้ด maintain ได้หรือเปล่า

---

# 📦 Prompt Set

---

## 🟢 Prompt 1: Landing Page (Basic)

```text
สร้างหน้า Landing Page สำหรับคอร์สสอนเขียนเว็บ โดยใช้ HTML, CSS, JavaScript แบบไม่ใช้ framework

เงื่อนไข:
- ต้องมี navbar, hero section, features section, testimonial section, pricing section, และ footer
- ออกแบบให้ดู modern และ responsive
- ใช้ semantic HTML
- ใช้ CSS แบบแยกไฟล์
- ใช้ JavaScript เพิ่ม mobile menu toggle
- ห้ามใช้ Bootstrap, Tailwind หรือ library ภายนอก
- โค้ดต้องอ่านง่ายและจัดระเบียบดี
- ใส่ comment อธิบายเฉพาะส่วนสำคัญ
- ส่งโค้ดครบทุกไฟล์: index.html, style.css, script.js
```

## 🟡 Prompt 2: To-Do List (Intermediate)

```text
สร้างเว็บ To-Do List ด้วย HTML, CSS, JavaScript แบบ pure vanilla

ความสามารถที่ต้องมี:
- เพิ่ม task
- ลบ task
- แก้ไข task
- mark ว่าทำเสร็จแล้ว
- filter: all / active / completed
- เก็บข้อมูลไว้ใน localStorage
- ถ้า input ว่างห้ามเพิ่ม task
- ต้อง responsive และ UI ดูดีเหมือนใช้งานจริง
- ใช้ semantic HTML
- แยกไฟล์เป็น index.html, style.css, script.js
- เขียนโค้ดให้ maintain ง่าย แยก function เป็นสัดส่วน
- อธิบาย logic การทำงานของ JavaScript หลังโค้ด
```

## 🔵 Prompt 3: Product Listing (Real-world)

```text
สร้างหน้า Product Listing สำหรับร้านขายสินค้าออนไลน์ด้วย HTML, CSS, JavaScript แบบไม่ใช้ framework

สิ่งที่ต้องมี:
- แสดงสินค้าอย่างน้อย 8 รายการจาก mock data
- มี search
- filter ตามหมวดหมู่
- sort ราคา
- add to cart
- cart sidebar
- เพิ่ม/ลดจำนวนสินค้า
- responsive
- semantic HTML
- แยก logic ชัดเจน
- ห้ามใช้ library ภายนอก
- ส่งโค้ดครบทุกไฟล์
```

## 🟣 Prompt 4: Register Form + Validation

```text
สร้างหน้า Register Form ด้วย HTML, CSS, JavaScript

เงื่อนไข:
- full name, email, password, confirm password
- validate real-time
- password >= 8 ตัว + uppercase + lowercase + number
- confirm password ต้องตรงกัน
- show/hide password
- error message ใต้ input
- responsive
- semantic HTML
- accessibility ดี
- แยกไฟล์ HTML/CSS/JS
```

## 🟠 Prompt 5: Admin Dashboard

```text
สร้าง Dashboard หน้า Admin ด้วย HTML, CSS, JavaScript

ฟีเจอร์:
- sidebar + navbar
- cards summary
- table users
- search + filter
- modal popup
- pagination
- dark mode
- responsive

ข้อกำหนด:
- mock data
- ห้ามใช้ library
- โค้ดต้องเป็นระบบ
```

## 🔴 Prompt 6: Responsive Focus

```text
สร้างเว็บบริษัทโดยเน้น responsive design

เงื่อนไข:
- navbar, hero, services, portfolio, contact
- รองรับ desktop / tablet / mobile
- ใช้ Flexbox + Grid
- ห้ามใช้ framework
- semantic HTML
```

## ⚫ Prompt 7: Weather App (Advanced)

```text
สร้าง Weather App ด้วย HTML, CSS, JavaScript

ฟีเจอร์:
- search เมือง
- current weather
- forecast 5 วัน
- loading / empty / error state
- เปลี่ยน theme ตามอากาศ
- responsive
- semantic HTML
- state management ชัดเจน
```

## 🧨 Prompt 8: Production-Level Test

```text
สร้าง Task Management App

ฟีเจอร์:
- CRUD task
- filter + search
- sort
- localStorage
- dark mode
- responsive

ข้อกำหนด:
- semantic HTML
- clean CSS
- JS แยก function
- handle edge cases
- review โค้ดตัวเอง
```

## 💥 Prompt Hardcore (Benchmark จริง)

```text
ฉันต้องการทดสอบ AI ด้าน front-end อย่างจริงจัง

ข้อห้าม:
- ห้ามเขียนโค้ดมั่วรวมกัน
- ห้าม UI แค่เดโม
- ห้าม ignore responsive
- ห้าม ignore accessibility

สิ่งที่ประเมิน:
- HTML structure
- CSS quality
- JS logic
- UX
- maintainability

จากนั้นให้สร้าง [project]
```

## 📊 Scoring System

```text
1. HTML (1-10)
✅ semantic
✅ structure

2. CSS (1-10)
✅ layout
✅ responsive
✅ spacing

3. JavaScript (1-10)
✅ logic
✅ structure
✅ bug

4. UX/UI (1-10)
✅ ใช้งานได้จริง
✅ ดู professional

5. Maintainability (1-10)
✅ อ่านง่าย
✅ ขยายต่อได้
```

## 🚀 Advanced Testing (Optional)

```text
เพิ่มคำสั่งนี้ท้าย prompt:

หลังจากเขียนเสร็จ:
- review โค้ดตัวเอง
- บอกจุดอ่อน
- แนะนำการ refactor
- แนะนำ production improvement
```
