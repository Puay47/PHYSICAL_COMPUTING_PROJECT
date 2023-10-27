# H3art beat
&emsp;&emsp;โครงงานนี้จัดทำขึ้นเพื่อเป็นส่วนหนึ่งของวิชา PHYSICAL COMPUTING เพื่อให้ได้ศึกษาหาความรู้ในเรื่องของการเขียนโปรแกรมภาษาC และการต่อบอร์ด Arduino โดยได้ศึกษาผ่านแหล่งความรู้ต่างๆ ไม่ว่าจะเป็นการศึกษาในห้องเรียนหรือการศึกษาด้วยตนเอง อาทิเช่น แหล่งความรู้จากเว็บไซต์ต่างๆ เป็นต้น ซึ่งในปัจจุบัน IoT (Internet of Things) ได้เข้ามามีบทบาทในชีวิตประจำวันเป็นอย่างมาก คณะผู้จัดทำจึงได้นำความรู้ทั้งหมดมาประยุกต์ใช้ทำโครงงานนี้ ซึ่งโครงงานที่จะนำเสนอนี้เป็นโครงงานทอยลูกเต๋าออนไลน์ เพื่อเพิ่มความสะดวกสบายในการใช้และช่วยลดทรัพยากรต่างๆ เนื่องจากลูกเต๋าเป็นสิ่งของที่มีขนาดเล็กทำให้เกิดการสูญหายและสิ้นเปลืองได้ง่าย ซึ่งผู้จัดทำคาดหวังเป็นอย่างยิ่งว่าการจัดทำโครงงานนี้จะมีข้อมูลที่เป็นประโยชน์ต่อผู้ที่สนใจศึกษาการพัฒนาเทคโนโลยีที่เกี่ยวข้องกับ IoT ต่อไปในอนาคต

# Poster
<img src="https://github.com/Puay47/PHYSICAL_COMPUTING_PROJECT/blob/main/Poster.png?raw=true" width="100%">

# ที่มาของโครงงาน
&emsp;&emsp;พวกเราเชื่อว่าใครหลายๆคนบางครั้งก็อยากที่จะวัดอัตราการเต้นของหัวใจของตัวเอง ซึ่งเครื่องวัดโดยทั่วไปแล้วส่วนใหญ่ก็มักจะอยู่ในโรงพยาบาล พวกเราจึงเล็งเห็นและสร้างเครื่องวัดอัตราการเต้นของหัวใจ ด้วยความรู้ที่ได้มาจากการเรียน PHYSICAL COMPUTING ในเรื่องของบอร์ด Arduino เราจึงได้ประกอบเครื่องวัดอัตราการเต้นของหัวใจขึ้นมาเพื่อตอบโจทย์สำหรับคนที่อยากรู้ว่าหัวใจของตัวเองเต้นเท่าไหร่ ยังไง และปกติมั้ยได้ในทันที และไม่เปลืองเงินและทรัพยากรอีกด้วย

# จุดประสงค์


# ประโยชน์


# อุปกรณ์
- Arduino UNO
<img src="https://www.ai-corporation.net/wp-content/uploads/2021/11/37_r1.jpg" width="150px">

- 128*32 OLED display
<img src="https://lzd-img-global.slatic.net/g/p/6d739bccf7392f6ae9298575e6e40262.jpg_720x720q80.jpg_.webp" width="150px">

- MAX30102 sensor
<img src="https://static.cytron.io/image/cache/catalog/products/SN-M30102-OXI/SN-M30102-OXI-a-512x512.jpg" width="150px">

- Jumper Wires
<img src="https://res.cloudinary.com/rsc/image/upload/b_rgb:FFFFFF,c_pad,dpr_1.0,f_auto,h_843,q_auto,w_1500/c_pad,h_843,w_1500/F7916450-01?pgw=1&pgwact=1" width="150px">

- buzzer module
<img src="https://www.spmicrotech.com/wp-content/uploads/2020/01/Passive-Buzzer-Module.jpg" width="150px">

# หลักการทำงาน
เซ็นเซอร์ MAX30102 ใช้แสงสว่างสองสี (แดงและเขียว) เพื่อวัดอัตราการเต้นของหัวใจและระดับออกซิเจนในเลือด (SpO2) โดยวัดการเปลี่ยนแปลงในความสว่างที่ผ่านผิวหนังเมื่อเลือดขยับตามการเต้นของหัวใจ

IR คือ ค่าตัวแปรแทน Checkforbeat (Check for Heartbeat หรือเช็คการเต้นหัวใจ) หาก เซ็นเซอร์ไม่สามารถตรวจจับการเต้นของหัวใจได้ จะให้แสดงบน OLED ว่า Please Place Your Finger

BPM คือ ค่าอัตราการเต้นของหัวใจ
นำค่า BPM ที่เซ็นเซอร์อ่านได้มาแสดงบน OLED โดยให้ดีเลย์ประมาณ 0.5 - 1 วินาที
<img src="https://github.com/Puay47/PHYSICAL_COMPUTING_PROJECT/blob/main/bbpng.png?raw=true">

โปรแกรมการทำงานของวงจร Smart Dice : https://www.tinkercad.com/things/0Q0A5c8MR0S-bodacious-luulia/editel?sharecode=c8WC7zmIZEIyshW-YH5nPVlcUAl67TDmga5AnHoQYaM


# YouTube สาธิตการทำงาน


# Source Code


# Member
1.      
2.      
3.      
4.      
&emsp;&emsp;รายงานนี้เป็นส่วนหนึ่งของวิชา PHYSICAL COMPUTING สาขาวิชาเทคโนโลยีสารสนเทศ ภาคเรียนที่ 1 ปีการศึกษา 2566
คณะเทคโนโลยีสารสนเทศ สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง
