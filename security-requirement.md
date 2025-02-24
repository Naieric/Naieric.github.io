# 5.1.4 Input Validation

**[Details](https://owasp.org/www-project-application-security-verification-standard)**
- Ensure structured data is strongly typed and validated against a defined schema (e.g., format, length, allowed characters).



 **[Chat GPT](https://chatgpt.com/)**
- กำหนดประเภทข้อมูลให้ชัดเจนและตรวจสอบความถูกต้องตามโครงสร้างที่กำหนด (เช่น รูปแบบ ความยาว อักขระที่อนุญาต)


**[Gemini](https://gemini.google.com/app)**
- ข้อมูลต้องมีรูปแบบที่แน่นอนและตรวจสอบความถูกต้องตาม Schema ที่กำหนดไว้ เพื่อให้ข้อมูลถูกต้องและเป็นระเบียบ (เช่น รูปแบบ ความยาว อักขระที่อนุญาต)



**Summary**
- การตรวจสอบข้อมูลนำเข้าที่มีโครงสร้าง เช่น JSON หรือ XML ควรมีการกำหนดประเภทข้อมูลอย่างชัดเจนและตรวจสอบตามสคีมา เพื่อให้แน่ใจว่าข้อมูลตรงตามข้อกำหนดด้านรูปแบบ ความยาว และอักขระที่อนุญาต ลดความเสี่ยงจากการโจมตีที่ใช้ข้อมูลไม่ถูกต้อง


**Example**
- การตรวจสอบรหัสผ่าน:
- ใช้สคีมาที่กำหนดข้อกำหนดของรหัสผ่าน เช่น ต้องมีความยาวอย่างน้อย 8 ตัวอักษร ประกอบด้วยตัวพิมพ์ใหญ่ ตัวพิมพ์เล็ก ตัวเลข และอักขระพิเศษ เพื่อเพิ่มความปลอดภัยและป้องกันการใช้รหัสผ่านที่คาดเดาได้ง่าย

 
**Members**

[6530250166 นายพิชานัต พรหมณี](https://naieric.github.io/security-requirement.html)

[6530250395 นายธนบดี บุญสุข](https://realalunda.github.io/security-requirement.html)
