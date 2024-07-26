เมื่อทำการ clone project ลงเครื่องแล้วให้ติดตั้ง python environment ด้วย<br>
`python -m venv .venv` หรือ `python3 -m venv .venv`
<br>
หลังจากนั้น เข้า Environment  <br>
หากเป็นของ window ใช้ `.venv/Script/activate` <br>
mac: `. .venv/bin/activate` <br>
<br>
หลังจากนั้นให้ติดตั้ง poetry สำหรับติดตั้ง package ต่าง ๆ ให้ตรงกับต้นฉบับ <br> ด้วย `pip install poetry` <br><br>

เมื่อติดตั้งเสร็จแล้วให้ใช้ `poetry install`  เพื่อทำการ install package ที่จำเป็นทั้งหมด สามารถดู package ต่าง ๆ ได้ที่ 
pyproject.toml
<br><br>
dataset.csv อยู่ใน folder ชื่อ datasets เป็นไฟล์ csv มี
feature ทั้งหมด 9 columns บวก 1 column เป็น timestamp
โดยมี feature ดังนี้ 
  1. `X Acceleration`
  2. `X Velocity`
  3. `X Displacement`
  4. `Y Acceleration`
  5. `Y Velocity`
  6. `Y Displacement`
  7. `Z Acceleration`
  8. `Z Velocity`
  9. `Z Displacement`

