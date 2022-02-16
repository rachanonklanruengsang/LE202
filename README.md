# LE202
# สรุป REPO Microcontroller และ lab

## Markdown 

- Header ใช้ # เพื่อทำตัวหนาตัวใหญ่ โดย ประโยคที่มี # 1 ตัวจะมีขนาดใหญ่ที่สุด และลดหย่อนลงมาตามจำนวน # ที่มากขึ้นหน้าประโยคนั้นๆ

- New line หากต้องการขึ้นบรรทัดใหม่ จะต้องเว้นบรรทัดให้ว่าง 1 บรรทัด และพิมพ์ในบรรทัดถััดไป ไม่งั้นคำจะติดกัน หรือสามารถใช้การกด Spacebar 2 ครั้งแทนได้

- Horizental line ใช้ - สร้างเส้นกั้นระหว่างบรรทัด

- Text style ทำตัวเอียงและตัวหนา ใช้ - หรือ * ครอบข้อความที่ต้องการให้เป็นตัวเอียง และใช้ -- หรือ ** ครอบข้อความที่ต้องการให้เป็นตัวหนา 

- Srtikethrough ใช้ขีดค่าข้อความที่ต้องการ โดยใช้ ~~ ครอบข้อความที่ต้องการจะขีดค่า

- Link หากต้องการให้ข้อความที่ผู้เข้าชมกดแล้วเชื่อมต่อไปยัง link ที่ต้องการ ให้ทำการ [] ครอบข้อความที่ต้องการจะ link และใส่ () ครอบ link ที่ต้องการ

- Image แทรกรูป ใช้เครื่องหมายคล้ายๆกับแทรก link !()[]

- List ใส่เครื่องหมาย - + * หน้าประโยคเพื่อความสวยงาม 

- Emoji แทรกอิโมจิ โดย กด :คร่อมชื่ออิโมจิ 🦖

## Microcontroller

- Digital ข้อมูลสัณญญาณไฟฟ้าแสดงในลักษณะเลขฐาน 2 ขึ้นตามแรรงดันไฟฟ้า

- Voltage แรงดันไฟ้า หรือ ความต่างศักย์ไฟฟ้าระหว่างจุด 2 จุด มี 2 ระบบ คือ ไฟฟ้ากระแสตรง (DC) และไฟฟ้ากระแสสลับ (AC)

- Computer เครือ่งมือหรืออุปกรณ์อิเล็กทรอนิกส์ ใช้ในการรคิดคำนวณทางคณณิจศาสตร์ตามคำสั่ง

- Internet  ระบบเครื่อข่ายเชื่อมต่ออุปกรณ์

- Program lag การเขียนคำสั่งทางคอมพิวเตอร์เพื่อใช้งานให้คอมพิวเตอร์ช่วยทำงาน คำนวณ

- Platformio การพัฒนาซอฟแวร์แบบเปิด 

## LAB

- Example 1 เขียนและใส่โปรแกรมเข้าไปใน microcontroller โดยในโปรแกรมข้างต้นมี 2 ส่วน ส่วนที่ 1 จะรันและจบไป ส่วนที่ 2 จะเป็น loop โดยให้การทำงานเป็นเพิ่มการนับขึ้นเรือ่ยๆ ทุกๆวินาที วินาทีละ 1 

- Example 2 เขียนโปรแกรมการค้นหา wifi เและใส่เข้าไปใน microcontroller มี 2 ส่วน เมือค้นเจอ wifi จะแสดง wifi ที่ค้นเจอทั้งหมด วนไปเรื่อยๆ

- Relay เชื่อมต่อ microcontroller ที่ลงโปีแกรม Exp1-2 กับ Relay เพื่อเปิด-ปิดสวิทช์

- Example 3 เขียนโปรแกรมเข้าไปใน miicrocontroller เชือ่มต่อ 2 port : input port และ output port โดยโปรแกรมทำงานในลักษณะ นับเพิ่มทีละ 1 ทุกๆ 0.5 วินาที ถ้าเป็นเลขคี่ให้เปิดสวิทช์ ถ้าเป็นเลขคู่ให้ปิด

- Example 4 เขียนโปรแกรมเข้าไปใน microcontroller เชื่อมต่อ 2 port : input port และ output port โดยโปรมแกรมจะทำงานในลักษณะ อ่านข้อมูลที่ input port หากเป็น 1 จะแสดงให้ปิดสวิทช์แต่เมื่อมีปัจจัยอื่นมากระทำจะส่งผลให้เปิด หรือคือถ้ามีแหล่งจ่ายไฟฟมากระทำที่ input port จะทำให้เกิดแสงสว่าง 

- Example 5 เขียนโปรแกรมเข้าไปใน miicrocontroller เพื่อเชื่อมต่อกับ wifi ที่ต้องการ เพื่อเข้าสู่ website 

- Example 6 เขียนโปรแกรมเข้าไปใน miicrocontroller สร้าง wiifi ให้ผู้อื่นเข้าเข้าใช้ และเปิดดู website ที่เรา link

## Microcontroller model 4 ตัว

### - IS61LV6416-10KLI-TR 

•	memorytype : SRAM  

•	speed : 10 ns

• memory size : 1 Mb

•	unit price : 122.9 บาท  

https://www.ozdisan.com/entegre-devreler-ics/hafiza-entegreleri/hafiza-entegreleri/IS61LV6416-10KLI-TR  

### - AT28C256-15PU  

•	memorytype : EEPROM   

•	speed : 150 mHz

• memory size : 256 KB 

•	unit price : 460.74 บาท 

https://www.ozdisan.com/entegre-devreler-ics/hafiza-entegreleri/hafiza-entegreleri/AT28C256-15PU

## - PIC16F72 I/SP

•	memorytype : Flash 

•	speed : 20 mHz

• memory size : 3.5 Mb 

•	unit price : 178.62 บาท  

https://www.robotistan.com/pic16f72-dip28-mikrodenetleyici

## - EN29LV800BB-70TIP

•	memorytype : Flash 

•	speed : 70 mHz

• memory size : 8 Mb 

•	unit price : 77.37 บาท  

https://www.ozdisan.com/entegre-devreler-ics/hafiza-entegreleri/hafiza-entegreleri/EN29LV800BB-70TIP

# สร้างการทดลองขึ้นมาเอง   
- เขียนโปรแกรมเข้าไปใน microcontroller ในลักษณะเดียวกับ Example 4 เมื่อมีสิ่งกระตุ้นเเข้ามาก็จะทำให้ microcontroller สั่งให้เปิดปิดสวิทช์ที่ต่ออยู่กับหลอดไฟ โดยสิ่งกระตุ้นของการทดลองนี้คือเมื่อถึงเวลาที่ต้องการจะสั่งให้เปิดไฟอัตโนมัติ

