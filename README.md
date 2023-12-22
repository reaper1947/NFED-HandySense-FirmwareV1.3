Handysense Firmware Version สำหรับการใช้งานกับ project ที่ต้องการใช้ Sensors ชนิดเดียวกันได้หลายตัว

    RS485 ให้แก้ไข Slave ของ sensors แล้วนำมาเปลี่ยนใน code 
    i2C   ให้ใช้ตัว TCA9548A ในการเพิ่ม Address ของ Sensors ลงไปและแก้ไขใน code เพิ่ม
  
การแก้ไขของ Code ตัวนี้มีสาเหตุเพื่อแก้ไขสำหรับ Project ที่ต้องการใช้ Sensors ประเภทเดียวกันหลายตัวในบอร์ดเพียงบอร์ดเดียวโดยไม่ต้อง layout บอร์ดขึ้นมาใหม่
  
======This code is generate for HandySense Board.======

So the original code from HandySense is too old version and i have to fix to created new Version 1.3 
This Git have 2 code about Version1.3 and 3slave RS485 or you can add more sensors to your project.
Enjoy!!
