## Laravel 8 & AdminLTE 3 & Auth 
### Install NPM Package & Composer Package

```
$ composer install   --> ติดตั้ง package ต่าง ๆ ของ php
```

```
$ npm i หรือ npm install   --> ติดตั้ง package ต่าง ๆ ของ node
```

###  Usage

1. Copy .env.example  -> ส้รางไฟล์ใหม่ชื่อ .env
2. Setup Env:  .env แก้ไขชื่อดาต้าเบสและรหัสผ่านให้ถูกต้อง
3. สร้างตารางโดยใช้คำสั่งด้านล่าง

```
$ php artisan migrate:fresh
```

### Run Project

```
$ php artisan serve
```

ใส่ port ที่ต้องการ
```
$ php artisan serve --port=9000
```
