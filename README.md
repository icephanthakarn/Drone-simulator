# 🚀 Drone Control Simulation (AR)

Drone Control Simulation คือแอปพลิเคชันที่ใช้ Augmented Reality (AR) สำหรับฝึกควบคุมโดรนในสภาพแวดล้อมจำลอง  
ช่วยให้ผู้ใช้งานสามารถฝึกทักษะการบิน ทดสอบซอฟต์แวร์ควบคุม และจำลองสถานการณ์จริงได้โดยไม่ต้องกังวลถึงความเสียหายของอุปกรณ์จริง


📲 Download APK
คุณสามารถติดตั้งแอปพลิเคชันบน Android ได้โดยดาวน์โหลดไฟล์ที่นี่:

👉 [Download Drone Simulator APK](./apk)


✨ Features
- Drone Flight States
  - 🟢 Idle – โดรนอยู่ในสถานะพัก
  - 🛫 Takeoff – โดรนเริ่มบินขึ้นจากพื้น
  - ✈️ Flying – บินอย่างอิสระ (ซ้าย/ขวา/หน้า/หลัง)
  - 🛬 Landing – โดรนลงจอดและหยุดทำงาน

AR Components
  - 🔍 AR Raycast – ตรวจจับตำแหน่งสำหรับวางโดรน  
  - 🟦 AR Plane – ตรวจจับและแสดงพื้นผิวจริง  
  - 🔄 AR Session – ควบคุม session ของ AR ทั้งหมด  
  - 🎥 XR Origin – ใช้คำนวณตำแหน่งและการเคลื่อนไหวของกล้อง  

Controllers
  - 🕹️ DroneController – จัดการ state และ animation ของโดรน  
  - ⚙️ GameManager – จัดการ UI และการเชื่อมต่อระหว่างผู้เล่นกับโดรน  


🎮 How to Play
1. ติดตั้งแอปจากไฟล์ APK บนสมาร์ทโฟน Android  
2. เปิดแอป → สแกนหาพื้นที่เรียบ (เช่น โต๊ะหรือพื้นห้อง)  
3. วางโดรนลงบนพื้นผ่าน AR Raycast  
4. ใช้ปุ่มควบคุมเพื่อ:  
   - Fly → ให้โดรนบินขึ้น  
   - Move → ควบคุมทิศทางการบิน  
   - Land → สั่งโดรนลงจอด   


🛠 Tech Stack
- Engine: Unity  
- Framework: AR Foundation  
- Language: C#  

