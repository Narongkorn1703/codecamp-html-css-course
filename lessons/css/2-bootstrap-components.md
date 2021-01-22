# Bootstrap Components 📦

Boostrap Components คือ HTML Elements สำเร็จรูปที่ถูกสร้างมาให้พร้อมใช้งานโดยที่เราไม่ต้องเขียน CSS เองเพื่อปรับแต่งหน้าตาของ Elements ลองมาดูตัวอย่างกันสักหน่อยดีกว่า

## Card Component

ให้ลองเอา Code ส่วนนี้ไปลองแปะดูใน HTML ระหว่าง <body></body> ไฟล์ของเราแล้วลอง Run ดูผลด้วย Live Server

```html
<div class="card" style="width: 18rem">
  <img
    src="https://via.placeholder.com/400x300"
    class="card-img-top"
    alt="card image"
  />
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">
      Some quick example text to build on the card title and make up the bulk of
      the card's content.
    </p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
```

## Form Component

ให้ลองเอา Code ส่วนนี้ไปลองแปะดูใน HTML ระหว่าง <body></body> ไฟล์ของเราแล้วลอง Run ดูผลด้วย Live Server

```html
<div style="width: 400px">
  <div class="mb-3">
    <label for="exampleFormControlInput1" class="form-label"
      >Email address</label
    >
    <input
      type="email"
      class="form-control"
      id="exampleFormControlInput1"
      placeholder="name@example.com"
    />
  </div>
  <div class="mb-3">
    <label for="exampleFormControlTextarea1" class="form-label"
      >Example textarea</label
    >
    <textarea
      class="form-control"
      id="exampleFormControlTextarea1"
      rows="3"
    ></textarea>
  </div>
</div>
```

## Button Components

ให้ลองเอา Code ส่วนนี้ไปลองแปะดูใน HTML ระหว่าง <body></body> ไฟล์ของเราแล้วลอง Run ดูผลด้วย Live Server

```html
<div>
  <button type="button" class="btn btn-primary">Primary</button>
  <button type="button" class="btn btn-secondary">Secondary</button>
  <button type="button" class="btn btn-success">Success</button>
  <button type="button" class="btn btn-danger">Danger</button>
  <button type="button" class="btn btn-warning">Warning</button>
  <button type="button" class="btn btn-info">Info</button>
  <button type="button" class="btn btn-light">Light</button>
  <button type="button" class="btn btn-dark">Dark</button>

  <button type="button" class="btn btn-link">Link</button>
</div>
```

## Exercises 🏅

ให้ลองสร้างหน้า Login ด้วย Bootstrap
