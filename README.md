# learn-XAMPP_

Turn on XAMPP
 - Window + x
 - Terminal (Admin)
 - สั่งปิด MyQSL80 : net stop MySQL80
 - เช็คว่าพอร์ตว่างแล้ว: netstat -aon | findstr :3306

Turn off XAMPP
- Window + x
- Terminal (Admin)
- สั่งเปิด MySQL80 : net start MySQL80

- เพราะ พอร์ต 3306 ถูก set defult เป็น MySQL80 ซึ่งจะ ชนกับ XAMPP
