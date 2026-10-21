# Database Setup 
สร้างฐานข้อมูล หรือใช้ฐานข้อมูลเดิมในไฟล์ .env.development ถ้ามีอยู่แล้ว และเพิ่มข้อมูลตัวอย่างไปที่ตาราง (ใช้เฉพาะการตั้งค่าครั้งแรกเท่านั้น และเมื่อ user ถามเรื่อง database setup หรือ seed data เท่านั้น)

## Command for migrate

```bash
npx prisma db push
```

## Seed Data

- ถ้า Database พร้อมแล้วให้รันคำสั่ง sql นี้ เพื่อเพิ่มข้อมูลเริ่มต้น `assets/insert_data_example.sql`