<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sora ร้านอาหารญี่ปุ่นมินิมอล</title>
  <style>
    body {
      font-family: 'Prompt', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5eee6;
      color: #333;
    }
    header {
      background-color: #e0d3c2;
      padding: 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #d4c4b1;
      padding: 0.5rem;
      gap: 1rem;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    footer {
      background-color: #e0d3c2;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
    .cta {
      text-align: center;
      margin: 2rem 0;
    }
    .cta button {
      background-color: #a98467;
      color: white;
      border: none;
      padding: 1rem 2rem;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sora ร้านอาหารญี่ปุ่นมินิมอล</h1>
    <p>อบอุ่น เรียบง่าย สไตล์ญี่ปุ่นแท้</p>
  </header>
  <nav>
    <a href="#menu">เมนู</a>
    <a href="#gallery">รูปภาพ</a>
    <a href="#contact">ติดต่อ</a>
    <a href="#booking">จองโต๊ะ</a>
    <a href="#reviews">รีวิว</a>
  </nav>

  <section id="menu">
    <h2>เมนูอาหาร</h2>
    <ul>
      <li>ซูชิรวม 320 บาท</li>
      <li>ราเมนโชยุ 180 บาท</li>
      <li>ข้าวหน้าปลาไหล 250 บาท</li>
    </ul>
    <div class="cta">
      <button>สั่งอาหารออนไลน์</button>
    </div>
  </section>

  <section id="gallery">
    <h2>แกลเลอรี</h2>
    <p>[รูปภาพอาหารและร้าน - รออัปโหลด]</p>
  </section>

  <section id="contact">
    <h2>ช่องทางติดต่อ</h2>
    <p>โทร: 062-470-6123</p>
    <p>LINE: @sorajapan</p>
<a href="https://facebook.com/ThammarakSoDa" target="_blank" rel="noopener">Facebook (Thammarak SoDa)</a>
    <p>Instagram: @sora.japan</p>
  </section>

  <section id="booking">
    <h2>จองโต๊ะ</h2>
    <form>
      <label>ชื่อ: <input type="text" name="name" /></label><br />
      <label>เบอร์โทร: <input type="tel" name="phone" /></label><br />
      <label>วันที่: <input type="date" name="date" /></label><br />
      <label>เวลา: <input type="time" name="time" /></label><br />
      <button type="submit">จอง</button>
    </form>
  </section>

  <section id="reviews">
    <h2>รีวิวจากลูกค้า</h2>
    <p>"อร่อยมาก บรรยากาศดีเหมือนอยู่ญี่ปุ่น!" - ลูกค้า A</p>
    <p>"เมนูหลากหลาย ราคาเหมาะสม แนะนำเลยครับ" - ลูกค้า B</p>
  </section>

  <section id="map">
    <h2>แผนที่ร้าน</h2>
    <p>[ฝัง Google Maps ที่นี่]</p>
  </section>

  <footer>
    <p>&copy; 2025 Sora Japanese Minimal Restaurant</p>
  </footer>
</body>
</html>

