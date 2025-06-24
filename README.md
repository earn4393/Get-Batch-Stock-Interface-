# Get Batch Stock Interface
- S : ต้องการหา material ที่สามารถนำมาใช้ทดแทนในการผลิดเพื่อให้การผลิตไม่หยุดชะงักและไม่ซื้อของเข้ามาเกินความจำเป็น (realtime)
- T : ออกแบบ SAP interface สำหรับใช้หา alternative material part ที่ใช้ผลิตแทน
- A : ออกแบบและทดสอบกับ user
- R : ผู้ใช้สามารถหา material ทดแทนจาก material ที่ขาดได้
## แตกต่างจาก Alternative Part Interface 
- รับ input field มากกว่า สโคปการหาข้อมูลได้ระเอียดขึ้น
- แสดงระเอียดกว่า เช่นถ้า material มีการโยกย้ายไปหลาย batch หลาย Material Get Batch Stock Interface  จะรู้ material ต้นและปลายทางด้วย แต่ alternative material part จะรู้แค่ bath ปลายทางเท่านั้น
## จุดเด่น
- ใช้ DFS ในการเขียน
