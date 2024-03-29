# Metaverse for Smart Factory Contest 2022
Repository นี้เป็นการเผยแพร่ผลงานการแข่งขัน [Metaverse for Smart Factory Contest 2022](https://smartfactory.hcilab.net/contest/metaverse2022/) ซึ่งผู้เข้าร่วมการแข่งขันยินยอมให้เผยแพร่ Source Code ทั้งหมดหรือบางส่วนของโปรแกรมจำลองการทำงาน (Simulation) โดยเป็น Source Code ส่วนการเชื่อมต่อระหว่างโปรแกรมจำลองการทำงาน (Simulation) และ TeleSorting System  มีวัตถุประสงค์เผยแพร่เพื่อให้นำไปใช้ในการศึกษา โดยมิได้อนุญาตให้นำไปใช้เชิงพาณิชย์ใด ๆ ทั้งสิ้น 

## ชื่อผลงาน โอเวอร์สอร์ท(Oversort)
### ที่มาและความสำคัญ
เนื่องจากแรงขับเคลื่อนทางด้านเศรษฐกิจและสังคม ไม่ว่าจะเป็นโครงสร้างประชากรที่เปลี่ยนแปลงไป ความเป็นเมืองในโลกขยายตัวหลายแห่ง ทำให้ประชากรมีรายได้สูงขึ้น ต้องการความเป็นอยู่ที่ดีและเกิดความต้องการสินค้า บริการที่มีความซับซ้อน คุณภาพสูง สิ่งเหล่านี้สะท้อนไปยังทั้งอุปสงค์และอุปทานของสินค้าในโลก ประเทศผู้ส่งออกที่ขาดแคลนแรงงาน จึงจำเป็นต้องหันไปหาเครื่องจักรอัตโนมัติเข้ามาแทนแรงงานคนในการผลิตสินค้า และต้องปรับตัวไปผลิตสินค้าที่มีคุณภาพในปริมาณมากหรือที่เรียกว่า “mass customization” ซึ่งเป็นที่มาของ การปฏิวัติอุตสาหกรรมในยุคที่ 4 หรือ Industry 4.0 ของอุตสาหกรรมในปัจจุบันและต่อไปในอนาคต
	แต่อย่างไรก็ตามในอนาคตเทคโนโลยีก็ต้องมีการเปลี่ยนแปลงเทคโนโลยีรูปแบบต่าง ๆ ทำให้เกิดการปรับเปลี่ยนจากภาคอุตสาหกรรม 4.0 เป็นภาคอุตสาหกรรม 5.0 (Industry 5.0) จึงเป็นที่มาถึงแนวโน้มการพัฒนาอุตสาหกรรม 5.0 (Industry 5.0) โดยรูปแบบแนวคิดของการการบูรณาการเทคโนโลยีสำหรับโรงงานอัจฉริยะ (Smart Factory) เพื่อพัฒนาไปสู่อุตสาหกรรม 5.0 (Industry 5.0) อาจจะเป็นการบูรณาการเทคโนโลยี “จักรวาลนฤมิต (Metaverse)” ที่สามารถให้ผู้ใช้งานระบบได้เข้ามามีปฏิสัมพันธ์ร่วมกับระบบโรงงานอัจฉริยะ ทำให้เกิดเป็นสภาพแวดล้อมเสมือนจริงที่สามารถเชื่อมต่อข้อมูลของโลกแห่งความจริง และเข้ามามีปฏิสัมพันธ์ร่วมกับระบบโรงงานอัจฉริยะ (Metaverse for Smart Factory) เสมือนว่ากำลังปฏิบัติงานอยู่ที่หน้างาน และสามารถรับข้อมูลการทำงานของอุปกรณ์ต่าง ๆ ภายในโรงงานได้แบบทันที (Real Time)
### วัตถุประสงค์
1. เพื่อพัฒนาประสิทธิภาพการทำงานของระบบจัดเรียงของระยะไกล (TeleSorting System) ในโรงงานอัจฉริยะ (Smart Factory) ด้วยแบบอัตโนมัติเต็มรูปแบบ
2. สามารถทำให้ผู้ใช้งานระบบได้เข้ามามีปฏิสัมพันธ์ร่วมกับระบบโรงงานอัจฉริยะ (Smart Factory) ผ่านการใช้เทคโนโลยี Metaverse
3. สามารถออกแบบระบบจัดเรียงของระยะไกล (TeleSorting System) ให้มีความสามารถ
### ประโยชน์ที่ได้รับ
1. ได้พัฒนาระบบการจัดเรียงของระยะไกล (TeleSorting System)
2. ได้เรียนรู้ พัฒนาทักษะการออกแบบ และเขียนโค้ดเพื่อควบคุมโปรแกรมการจำลองการทำงานของโรงงานอัจฉริยะร่วมกับระบบจัดเรียงของระยะไกล (TeleSorting System)
3. ได้เรียนรู้ทักษะการทำงานเป็นทีม และสามารถทำงานให้สำเร็จลุล่วงได้
### ภาพรวมระบบ
สามารถตรวจจับสีและแยกสีของกล่องได้อย่างมีประสิทธิภาพ อีกทั้งยังสามารถใช้ฟังก์ชั่นชี้สีผ่านกล้องเพื่อเลือกสีในการปล่อยกล่องให้ระบบคัดแยก
![Screenshot (853)](https://user-images.githubusercontent.com/114386015/196618587-da796dc2-d48c-43f6-b726-46c00c79f429.png)

### คลิปนำเสนอผลงาน
https://youtu.be/j8lfr_UO02I

## รายชื่อสมาชิกทีมACSP
1. อภิรักษ์ แซ่จิว
2. ธีร์ธวัช ฝ่ายคำมี
3. วาธิน พรมฝ้าย
4. ธนวินท์ หลินศุวนนท์
5. กันตพัฒน์ กรวิชญ์สิริชัย
6. ภัทรเดช อัครวรนนท์
7. ณัฐพัชร เจริญรัตน์ประทุม
8. ภูรินทร์ มั่นทอง
9. ปัญญากร โปษยาอนุวัตร์ 
10. ณัฏฐชัย ยอดกุล
## ช่องทางการติดต่อ
Email: job4450@gmail.com  
