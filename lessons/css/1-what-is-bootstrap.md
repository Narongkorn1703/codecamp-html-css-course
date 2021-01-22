# What is Bootstrap 🛠

Bootstrap คือ เครื่องมือในการช่วยสร้าง Frontend ในเรื่องของ Responsive, mobile-first, etc.

## Feature ที่สำคัญของ Bootstrap ⭐️

1. Components - HTML Elements สำเร็จรูปที่ถูกสร้างมาให้พร้อมใช้งานโดยที่เราไม่ต้องเขียน CSS เองเพื่อปรับแต่งหน้าตาของ Elements
2. Layout - ระบบ Layout ที่ช่วยให้วาง Layout บนหน้าเว็บให้ง่ายยิ่งขึ้น
3. Utilities - CSS class ที่สร้างมาไว้ให้แล้ว
4. Customisation - เนื่องจาก Bootstrap มี Component สำเร็จรูปให้เราใช้ เราสามารถที่จะแก้ไข สี ขนาด ต่าง ๆ ของ Component ให้เป็นแบบที่เราต้องการได้

## เริ่ม Setup Bootstrap กันก่อน 🧑‍💻

0. สร้าง Folder Project ขึ้นมาใหม่ชื่อ `learn-bootstrap` จากนั้นให้ทำการเขียน HTML ไปดังนี้

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Learn Bootstrap</title>
  </head>
  <body></body>
</html>
```

1. ให้ทำการ Link ไฟล์ CSS ของ Bootstrap เข้ามาใน Project กันก่อน

```html
<head>
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1"
    crossorigin="anonymous"
  />
</head>
```

2. จากนั้นให้ Link ไฟล์ JavaScript เข้ามาใน Project ของเราด้วยเช่นกัน

```html
<body>
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
    crossorigin="anonymous"
  ></script>
</body>
```

3. Code ทั้งหมดจะมีหน้าตาประมาณนี้

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Learn Bootstrap</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
```
