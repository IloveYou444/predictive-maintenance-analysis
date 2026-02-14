<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kittithouch - Portfolio</title>
    <style>
        /* ตั้งค่าพื้นหลังสีมืดและฟอนต์ */
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0b0914; /* สีพื้นหลังดำดุดัน */
            color: white;
            overflow-x: hidden;
        }

        /* เมนูด้านบน (Navigation Bar) */
        .navbar {
            display: flex;
            justify-content: flex-end;
            padding: 30px 50px;
            gap: 40px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
            transition: 0.3s;
        }
        .navbar a:hover {
            color: #b400ff; /* สีม่วงตอนเอาเมาส์ชี้ */
        }

        /* จัด Layout ซ้าย-ขวา */
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-around;
            padding: 50px 10vw;
            min-height: 70vh;
        }
        .hero-text {
            max-width: 50%;
        }

        /* ตกแต่งข้อความฝั่งซ้าย */
        .greeting {
            background: #2a1b38;
            padding: 8px 16px;
            border-radius: 20px;
            display: inline-block;
            margin-bottom: 20px;
            font-size: 14px;
            color: #e0b0ff;
        }
        h1 {
            font-size: 4rem;
            margin: 0;
            /* ไล่สีตัวหนังสือ I'm Kittithouch */
            background: -webkit-linear-gradient(0deg, #ffffff, #b400ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        h2 {
            font-size: 1.8rem;
            font-weight: normal;
            color: #cccccc;
            margin-top: 10px;
        }
        p {
            color: #999999;
            line-height: 1.6;
            font-size: 1.1rem;
        }

        /* ตกแต่งรูปภาพฝั่งขวา (Glowing Effect!) */
        .hero-image img {
            width: 380px;
            height: 380px;
            border-radius: 30px;
            object-fit: cover;
            /* นี่คือโค้ดสร้างแสงเรืองแสงสีม่วง/ชมพู แบบในรูปเป๊ะ! */
            box-shadow: 0 0 60px 10px rgba(180, 0, 255, 0.5); 
            transition: 0.5s;
        }
        .hero-image img:hover {
            box-shadow: 0 0 80px 20px rgba(180, 0, 255, 0.8);
            transform: scale(1.02);
        }

        /* ปุ่มกดไปหน้าโปรเจกต์ */
        .buttons {
            margin-top: 40px;
        }
        .btn {
            padding: 15px 30px;
            background: linear-gradient(90deg, #6a00f4, #b400ff);
            color: white;
            text-decoration: none;
            border-radius: 12px;
            font-weight: bold;
            font-size: 1.1rem;
            transition: 0.3s;
            display: inline-block;
            box-shadow: 0 5px 15px rgba(180, 0, 255, 0.4);
        }
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(180, 0, 255, 0.6);
        }
    </style>
</head>
<body>

    <div class="navbar">
        <a href="#">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </div>

    <div class="hero">
        <div class="hero-text">
            <div class="greeting">👋 สวัสดี ยินดีต้อนรับ</div>
            <h1>I'm Kittithouch</h1>
            <h2>Business Analyst & Data Strategy</h2>
            <p>สร้างสรรค์กลยุทธ์ธุรกิจและการวิเคราะห์ข้อมูล (Data Analytics) ที่สวยงาม ใช้งานง่าย และมีประสิทธิภาพ เพื่อใช้ต่อยอดในการตัดสินใจและการลงทุน</p>
            
            <div class="buttons">
                <a href="project.html" class="btn">🚀 ดูผลงาน Predictive Maintenance</a>
            </div>
        </div>

        <div class="hero-image">
            <img src="profile.jpg" alt="Kittithouch Profile">
        </div>
    </div>

</body>
</html>
