# H3art beat
&emsp;&emsp;โครงงานนี้จัดทำขึ้นเพื่อเป็นส่วนหนึ่งของวิชา PHYSICAL COMPUTING เพื่อให้ได้ศึกษาหาความรู้ในเรื่องของการเขียนโปรแกรมภาษาC++ และการต่อบอร์ด Arduino โดยได้ศึกษาผ่านแหล่งความรู้ต่างๆ ไม่ว่าจะเป็นการศึกษาในห้องเรียนหรือการศึกษาด้วยตนเอง อาทิเช่น แหล่งความรู้จากเว็บไซต์ต่างๆ เป็นต้น ซึ่งในปัจจุบัน IoT (Internet of Things) ได้เข้ามามีบทบาทในชีวิตประจำวันเป็นอย่างมาก คณะผู้จัดทำจึงได้นำความรู้ทั้งหมดมาประยุกต์ใช้ทำโครงงานนี้ ซึ่งโครงงานที่จะนำเสนอนี้เป็นโครงงานเครื่องวัดอัตราการเต้นของหัวใจ เพื่อเพิ่มความสะดวกสบายในการใช้และช่วยลดทรัพยากรต่างๆ ไม่ต้องไปถึงโรงพยาบาล และหันมารักสุขภาพกันมากขึ้น ซึ่งผู้จัดทำคาดหวังเป็นอย่างยิ่งว่าการจัดทำโครงงานนี้จะมีข้อมูลที่เป็นประโยชน์ต่อผู้ที่สนใจศึกษาการพัฒนาเทคโนโลยีที่เกี่ยวข้องกับ IoT ต่อไปในอนาคต

# Poster
<img src="https://github.com/Puay47/PHYSICAL_COMPUTING_PROJECT/blob/main/Poster.png?raw=true" width="100%">

# ที่มาของโครงงาน
&emsp;&emsp;พวกเราเชื่อว่าใครหลายๆคนบางครั้งก็อยากที่จะวัดอัตราการเต้นของหัวใจของตัวเอง ซึ่งเครื่องวัดโดยทั่วไปแล้วส่วนใหญ่ก็มักจะอยู่ในโรงพยาบาล พวกเราจึงเล็งเห็นและสร้างเครื่องวัดอัตราการเต้นของหัวใจ ด้วยความรู้ที่ได้มาจากการเรียน PHYSICAL COMPUTING ในเรื่องของบอร์ด Arduino เราจึงได้ประกอบเครื่องวัดอัตราการเต้นของหัวใจขึ้นมาเพื่อตอบโจทย์สำหรับคนที่อยากรู้ว่าหัวใจของตัวเองเต้นเท่าไหร่ ยังไง และปกติมั้ยได้ในทันที และไม่เปลืองเงินและทรัพยากรอีกด้วย

# จุดประสงค์
- เพื่อให้ได้รับความสะดวกและรวดเร็วในการวัดอัตราการเต้นของหัวใจ
- เพื่อเป็นสื่อในการเรียนการสอน
- ทุกคนในกลุ่มสามารถที่จะสร้างวงจรเพื่อวัดอัตราการเต้นของหัวใจได้ 


# ประโยชน์
- ติดตามสุขภาพหัวใจ : ช่วยในการควบคุมและเฝ้าระวังสุขภาพของหัวใจ
- ควบคุมการออกกำลังกาย : ช่วยในการตรวจสอบการออกกำลังกายและให้ข้อมูลเกี่ยวกับการเผาผลาญแคลอรี่และความพยายามทางกายเพื่อสุขภาพที่ดี
- เสริมสร้างสุขภาพทางกายและจิตใจ : การมีข้อมูลแสดงอัตราเต้นของหัวใจสามารถทำให้คุณให้ความสำคัญกับสุขภาพทางกายและจิตใจ และยังสร้างสติปัญญาในการดูแลตัวเองอีกด้วย


# อุปกรณ์
- Arduino UNO
<img src="https://www.ai-corporation.net/wp-content/uploads/2021/11/37_r1.jpg" width="150px">

- 128*32 OLED display
<img src="https://lzd-img-global.slatic.net/g/p/6d739bccf7392f6ae9298575e6e40262.jpg_720x720q80.jpg_.webp" width="150px">

- MAX30102 sensor
<img src="https://cdn.discordapp.com/attachments/1065650055199076482/1167856157218578442/0j.png?ex=654fa5cd&is=653d30cd&hm=5a6fb6b96ec0b04258d153803c9ac0260db412d7ef3a2cd93ecbb7333487e160&" width="150px">

- Jumper Wires
<img src="https://res.cloudinary.com/rsc/image/upload/b_rgb:FFFFFF,c_pad,dpr_1.0,f_auto,h_843,q_auto,w_1500/c_pad,h_843,w_1500/F7916450-01?pgw=1&pgwact=1" width="150px">

- buzzer module
<img src="https://www.spmicrotech.com/wp-content/uploads/2020/01/Passive-Buzzer-Module.jpg" width="150px">

# หลักการทำงาน
เซ็นเซอร์ MAX30102 ใช้แสงสว่างสองสี (แดงและเขียว) เพื่อวัดอัตราการเต้นของหัวใจและระดับออกซิเจนในเลือด (SpO2) โดยวัดการเปลี่ยนแปลงในความสว่างที่ผ่านผิวหนังเมื่อเลือดขยับตามการเต้นของหัวใจ

IR คือ ค่าตัวแปรแทน Checkforbeat (Check for Heartbeat หรือเช็คการเต้นหัวใจ) หาก เซ็นเซอร์ไม่สามารถตรวจจับการเต้นของหัวใจได้ จะให้แสดงบน OLED ว่า Please Place Your Finger

BPM คือ ค่าอัตราการเต้นของหัวใจ
นำค่า BPM ที่เซ็นเซอร์อ่านได้มาแสดงบน OLED โดยให้ดีเลย์ประมาณ 0.5 - 1 วินาที
<img src="https://github.com/Puay47/PHYSICAL_COMPUTING_PROJECT/blob/main/Board.png?raw=true">

โปรแกรมการทำงานของวงจร H3art beat : https://www.tinkercad.com/things/3JnHlTND9Nj?sharecode=hy-xesalI0QL_Er3QbQkShSM_nw5H6JsT_sgqaOMocg
## เนื่องจากtinkercad ไม่สามารถแสดงสิ่งที่เราทำได้ เนื่องจากไม่มีอุปกรณ์ลองรับ เราเลยทำการจำลองขึ้นมาให้เหมือนกับสิ่งที่เราทำที่สุด


# YouTube สาธิตการทำงาน
https://youtube.com/shorts/QP3tDHv4xtg?si=jpfG4u_MENQNA-tv

# Source Code

<img src="https://cdn.discordapp.com/attachments/1065650055199076482/1167861524916863086/image.png?">
<img src="https://cdn.discordapp.com/attachments/1065650055199076482/1167861525327908904/image.png?">
<img src="https://cdn.discordapp.com/attachments/1065650055199076482/1167861525676048535/image.png?">

# Member
1. นายกิตติพัฒน์ เอี่ยมลือนาม 65070020
2. นายจารุพงศ์ ทองมาก 65070031
3. นายศิวกร สมจิตร์ 65070220
4. นางสาวรุ่งนภา แช่มชื่น 65070199
   
&emsp;&emsp;รายงานนี้เป็นส่วนหนึ่งของวิชา PHYSICAL COMPUTING สาขาวิชาเทคโนโลยีสารสนเทศ ภาคเรียนที่ 1 ปีการศึกษา 2566
คณะเทคโนโลยีสารสนเทศ สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง
