# FRA_502_Service
นายสัณห์ศิวัช เกื้อกูลสง 62340500053

# การรันโค้ต (ใน terminal)
1.roscore 
2.source catkin_ws/devel/setup.bash
3.launch robot_sim run.launch
4.launch robot_sim navigation.launch
5.launch robot_sim goal.launch
**ถ้า goal.launch รันไม่ได้ ให้เข้าไปที่ directory ของไฟล์ goal.py เเล้วพิมพ์ chmod +x goal.py**

# การสั่งงานด้วยเสียง
1.รอคำสั่งเสียง เช็กไมโครโฟน
![image](https://user-images.githubusercontent.com/78643149/145625453-5d93e705-156f-4646-bb22-7f24cd097519.png)

2.พร้อมรับคำสั่ง
![image](https://user-images.githubusercontent.com/78643149/145625734-e7e7b8ab-3898-42db-bf23-a891e428146b.png)

3.ถ้าไม่มีการพูด หรือโปรแกรมไม่ได้รับเสียง
~~~~~~![image](https://user-images.githubusercontent.com/78643149/145625941-1a9c7283-e797-4f3d-8ddd-27cdbf14f95c.png)

4.คำสั่งเสียงมี 5 แบบ 
![image](https://user-images.githubusercontent.com/78643149/145629839-95440a65-d618-40db-852d-da62980fadf8.png)

เมื่อได้ยินเสียงหุ่นจะเคลื่อนที่ไปยังตำแหน่งที่ตั้งไว้
![image](https://user-images.githubusercontent.com/78643149/145629910-f95b5670-8645-47a1-9536-944ebe9f7e88.png)

5.เมื่อไปถึงจุดหมาย หุ่นจะเคลื่อนที่ไปยังตำแหน่งเริ่มต้นเพื่อรอคำสั่งต่อไป
![image](https://user-images.githubusercontent.com/78643149/145623145-54ac3ac9-bd46-4f28-a213-bd0e00646d10.png)

# ปัญหาที่พบ
1.fpsต่ำ ทำให้ภาพกระตุก การบังคับหุ่นหรือสำรวจแมพทำได้ยาก
2.ไมโครโฟนมีเสียงที่เบา ทำให้การสั่งงานด้วยเสียงมีความล่าช้า หรืออาจทำงานไม่ได้
3.
