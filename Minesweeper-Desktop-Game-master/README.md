Minesweeper Desktop Game 🚩
Minesweeper Desktop Game เป็นเกมถอดรหัสกับดักระเบิด (Minesweeper) เวอร์ชันเดสก์ท็อปที่พัฒนาด้วยภาษา Java พร้อมส่วนติดต่อผู้ใช้ (GUI) ที่ใช้งานง่าย เข้าถึงสนุก และคงเสน่ห์ความคลาสสิกของเกมกู้ระเบิดไว้อย่างครบถ้วน

🛠️ คุณสมบัติหลัก (Features)
คลาสสิกเล่นง่าย: ระบบการเล่นคงเอกลักษณ์ดั้งเดิมของ Minesweeper ไว้ทั้งหมด

ระบบปักธง (Flagging): รองรับการคลิกขวาเพื่อปักธงหรือทำเครื่องหมายจุดที่สงสัยว่าเป็นระเบิด

ตรวจจับการแพ้/ชนะ: ระบบคำนวณและแจ้งเตือนสถานะจบเกมทันทีเมื่อเปิดเจอระเบิด หรือเมื่อเปิดช่องที่ปลอดภัยครบทั้งหมด

ส่วนต่อประสานผู้ใช้ (GUI): หน้าต่างเดสก์ท็อปสะอาดตา แสดงผลตัวเลขจำนวนระเบิดรอบข้างชัดเจน

💻 เทคโนโลยีและไลบรารีที่ใช้ (Tech Stack)
Language: Java

UI Framework: Java Swing / AWT

Dependencies & Libraries (อยู่ในโฟลเดอร์ Code/Libs/):

commons-lang-2.6.jar

commons-logging-1.1.1.jar

hsqldb-2.3.1.jar (ฐานข้อมูล HSQLDB สำหรับเก็บสถิติ/ข้อมูลภายใน)

📂 โครงสร้างโฟลเดอร์ (Directory Structure)
Plaintext
Minesweeper-Desktop-Game-master/
├── Code/                  # ซอร์สโค้ดหลักของโปรเจกต์
│   └── Libs/              # ไฟล์ Jar Dependencies ที่จำเป็น
├── .github/               # การตั้งค่า GitHub และ Funding
├── .gitattributes
└── README.md              # เอกสารอธิบายโปรเจกต์
🚀 วิธีการติดตั้งและเริ่มต้นใช้งาน (Getting Started)
1. ความต้องการของระบบ (Prerequisites)
ติดตั้ง Java Development Kit (JDK 8) หรือเวอร์ชันที่สูงกว่า

IDE สำหรับพัฒนา เช่น IntelliJ IDEA, Eclipse, NetBeans หรือ VS Code

2. การรันโปรเจกต์ (Run Project)
Clone Repository นี้ลงเครื่องคอมพิวเตอร์ของคุณ:

Bash
git clone https://github.com/mangKorn497/Minesweeper-Desktop-Game-master.git
เปิดโปรเจกต์ ผ่าน IDE ที่คุณใช้งาน

ตั้งค่า Classpath / External Libraries:

เพิ่มไฟล์ .jar ทั้งหมดที่อยู่ในโฟลเดอร์ Code/Libs/ เข้าไปยัง Build Path หรือ Classpath ของ IDE

Compile และ Run:

ค้นหา Class ที่มีเมธอด main (เช่น Main.java หรือ App.java ภายในโฟลเดอร์ Code/) แล้วทำการรันเพื่อเริ่มเล่นเกม

🎮 วิธีการเล่น (How to Play)
คลิกซ้าย: เปิดช่องที่ต้องการ

ตัวเลขบนช่อง: แสดงจำนวนระเบิดที่อยู่ติดกับช่องนั้นๆ (ในรัศมี 8 ทิศทาง)

คลิกขวา: ปักธง 🚩 ตรงช่องที่คาดว่ามีระเบิด

เป้าหมาย: เปิดช่องที่ปลอดภัยทั้งหมดโดยไม่กดโดนระเบิด!




