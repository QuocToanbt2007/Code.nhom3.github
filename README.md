<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Nhóm 3</title>
    <style>
        body {
            margin: 0;
            font-family: cursive;
            background: linear-gradient(to bottom, #D2B48C, white);
            text-align: center;
        }
        .header {
            background: #D2B48C;
            color: white;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        .main-image {
            margin: 20px auto;
            width: 50%;
        }
        .links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            padding: 20px;
        }
        .links a {
            text-decoration: none;
            color: black;
            text-align: center;
        }
        .links img {
            width: 100px;
            height: 100px;
            border-radius: 10px;
            display: block;
        }
        .form-section {
            background: white;
            padding: 20px;
            margin: 20px auto;
            width: 40%;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }
        .footer {
            background: #D2B48C;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="header"> WELCOME TO BOY GROUP </div>
    <a href="#"><img class="main-image" src="main.jpg" alt="Ảnh chính"></a>
    <div class="links">
        <a href="https://quoctoanbt2007.github.io/Annhom3.com/">
            <img src="https://s.pro.vn/hcoR" alt="Thien An ">
        </a>
        <a href="https://quoctoanbt2007.github.io/Baonhom3.com/">
            <img src="https://short.com.vn/VPwa" alt=" Gia Bao ">
        </a>
        <a href="https://quoctoanbt2007.github.io/Duynhom3.com/">
            <img src="https://s.pro.vn/Aoi0" alt="	Trọng Duy">
        </a>
        <a href="https://quoctoanbt2007.github.io/Toannhom3.com/">
            <img src="https://s.pro.vn/LNg7" alt="Quốc Toản">
        </a>
		
    
    <div class="form-section">
        <h3> Give your information </h3>
        <form>
            <label>Phone:</label><br>
            <input type="text" name="name" required><br>
            <label> Phone:</label><br>
            <input type="tel" name="phone" required><br>
            <label>Email:</label><br>
            <input type="email" name="email" required><br><br>
            <button type="submit">Send </button>
        </form>
    
    <div class="footer"> Website made by group 3</div>
