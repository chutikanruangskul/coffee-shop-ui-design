# ☕ Coffee Shop UI/UX Wireframe Design

ตัวอย่างการออกแบบ Wireframe สำหรับระบบร้านกาแฟ (Coffee Shop Application / Website) 

## 🔗 Figma Project
สามารถเข้าชมงานออกแบบตัวเต็มและ Interactive Prototype ได้ที่:
👉 [คลิกที่นี่เพื่อดูงานบน Figma](https://www.figma.com/design/EFPzR1BnAdRIn30cggw5SN/Wireframe?node-id=0-1&t=5f1r4wCbdLUgdHPE-1)

## 📐 Wireframe Overview & Phases
คำอธิบายสรุปเกี่ยวกับการแบ่งขั้นตอนการทำงานและการกำหนดสิทธิ์การใช้งาน (Role-based Access Control)

🔹 Phase A: Low-Fidelity Wireframes & Core Features
ในระยะนี้เน้นการวางโครงร่างและ Layout พื้นฐานของระบบการขายหน้าร้าน (POS) รวมถึงการกำหนดสิทธิ์ผู้ใช้งานเบื้องต้น:

ความแตกต่างระหว่างเจ้าของร้าน (Manager/Owner) และ พนักงาน (Staff):
    
    จุดที่เหมือนกัน: ทั้งสองสิทธิ์สามารถเข้าถึงหน้า การขายสินค้า (POS) เพื่อทำรายการสั่งซื้อ คิดเงิน ออกใบเสร็จ และดูหน้า การจัดการคลังสินค้า เพื่อตรวจสอบรายการวัตถุดิบและสินค้าคงเหลือได้
    
    จุดที่แตกต่าง: แถบเมนูด้านข้าง (Sidebar Menu) ของเจ้าของร้านจะถูกออกแบบให้มีเมนูการบริหารจัดการระดับสูงครบถ้วน เพื่อเตรียมพร้อมสำหรับการขยายฟังก์ชันในเฟสถัดไป 
    ขณะที่เมนูของพนักงานจะถูกจำกัดให้เห็นเฉพาะเมนูที่จำเป็นต่อการปฏิบัติงานหน้าร้านเท่านั้น (หน้าหลัก, การขายสินค้า, การจัดการคลังสินค้า)   

🔹 Phase B: High-Fidelity UI Design & Full Management System
ในระยะนี้เป็นการลงรายละเอียดงานออกแบบจริง (High-Fidelity) พร้อมเพิ่มระบบบริหารจัดการหลังร้านสำหรับเจ้าของร้านแบบเต็มรูปแบบ:

ฟังก์ชันเฉพาะสำหรับเจ้าของร้าน (Manager / Owner):
  1. การจัดการคลังสินค้า (Stock Management): ตรวจสอบ เพิ่ม แก้ไข สต็อกวัตถุดิบและสินค้าคงเหลือ พร้อมระบบแจ้งเตือนสินค้าใกล้หมด
  2. การจัดการลูกค้า (Customer Management): จัดการข้อมูลสมาชิก ค้นหาประวัติการซื้อ และบริหารจัดการระบบสะสมคะแนน
  3. การจัดการคำสั่งซื้อ (Order Management): ตรวจสอบรายการสั่งซื้อย้อนหลัง ประวัติการขาย และยอดขายรวม
  4. การจัดการพนักงาน (Staff Management): เพิ่ม ลบ หรือแก้ไขข้อมูลพนักงานในร้าน
  5. การจัดการผู้ใช้งาน (User Management): กำหนดสิทธิ์การเข้าถึงระบบและควบคุมการใช้งานของบัญชีต่างๆ

🎨 UI Specification & Design System
  1. Color Palette (โทนสีระบบ)
       • Primary Background (พื้นหลังหลัก): #FDE2C8 (ครีมอ่อน) — ช่วยให้หน้าจอสบายตา เด่นชัด ไม่เมื่อยล้าสายตาขณะใช้งาน

       • Header & Sidebar (แถบนำทางและส่วนหัว): #64483C (น้ำตาลเข้ม) — สร้างความชัดเจนและแบ่งสัดส่วนเมนูหลัก

       • Selection & Primary Buttons (ปุ่มเลือก/การกระทำหลัก): #FFBD60 (ส้มอ่อน) — ดึงดูดสายตาสำหรับจุดที่ต้องคลิกหรือยืนยันรายการ

       • Text & Typography (ข้อความทั่วไป): #64483C (น้ำตาลเข้ม) บนพื้นหลังสีอ่อน เพื่อให้อ่านง่ายและชัดเจน

       • Container & Cards (พื้นหลังเนื้อหาเน้นย้ำ): #96704B (น้ำตาลอ่อน) — สร้างมิติและความแตกต่างให้กล่องข้อมูล

       • Icons & Graphics (ไอคอนและกราฟิก): #96704B / #FFD5B — เพิ่มความสวยงามและน่าสนใจ
  
  3. Typography & Layout Specifications (ตัวอย่าง Login Page)
       • Font Family: TH Sarabun New

       • Title Bar:  Background Color: #64483C | Font Color: #FFFFFF | Font Size: 36px Regular
                    Dimension: Width 1440px | Height 52px

       • Login Frame/Panel:  Background Color: #FDE2C8 | Border Radius: 30px | Stroke: #C19A6B

       • Input Fields (Username / Password):  Background Color: #96704B (Fill 50%) | Font Color: #FFFFFF | Font Size: 24px Regular
                                          Dimension: Width 426px | Height 80px

       • Primary Button (เข้าสู่ระบบ):  Background Color: #64483C | Font Color: #FFFFFF | Font Size: 36px | Border Radius: 20px
                                 Dimension: Width 426px | Height 70px

### ตัวอย่างการออกแบบ
<img width="1095" height="787" alt="image" src="https://github.com/user-attachments/assets/a3f91d40-d4dc-4a11-afc7-ddfaba24f894" />
<img width="1073" height="798" alt="image" src="https://github.com/user-attachments/assets/e690185d-cd8b-4725-ad34-c75a41006821" />
<img width="1068" height="801" alt="image" src="https://github.com/user-attachments/assets/1987234c-eaae-4065-8c15-48db1dbde9bc" />
<img width="1000" height="753" alt="image" src="https://github.com/user-attachments/assets/af96155b-5a12-429c-a4be-23da1c59c4b5" />
<img width="1017" height="757" alt="image" src="https://github.com/user-attachments/assets/b36cda60-b1c5-43a7-a3ce-de0800096308" />
<img width="987" height="572" alt="image" src="https://github.com/user-attachments/assets/70b2ecf6-dfaa-4ee6-9304-f2f0d3bfaf87" />
<img width="962" height="655" alt="image" src="https://github.com/user-attachments/assets/f2e4addd-df0c-48e6-9094-e3e23c9fbd29" />

## 🛠 เครื่องมือที่ใช้
การออกแบบและการจำลองโครงร่าง : Figma
