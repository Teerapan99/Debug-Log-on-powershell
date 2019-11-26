# Debug-Log-on-powershell 
ทำการส้ราง Foder เพื่อเก็บไฟล์ Log 
                 
     1.เช่น Foder Result แล้วสร้างไฟล์ debug.log 
     
     2.ใช้คำสั่ง on-powershell Get-Content -Wait -Path debug.log 
  
     Note: ต้องเข้าไปที่ Path ที่เก็บไฟล์ก่อนใช้คำสั่ง
 
 จากนั้น เปิด powershell อีกตัวนึง ไปที่ Path ที่เก็บไฟล์ .robot ใช้คำสั่ง robot -d result -L trace -b debug.log robot_test.robot
 
     Note: ชื่อไฟล์ .robot ห้ามมีเว้นวรรค
