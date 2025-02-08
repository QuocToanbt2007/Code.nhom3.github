<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TRỌNG DUY </title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Lora:wght@400;700&display=swap');

        body {
            font-family: 'Lora', serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        /* Pano đầu trang */
        .header {
            background: linear-gradient(to bottom, #ffd1a9, white);
            padding: 20px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            color: #333;
        }

        /* Khung giữa trang */
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 20px auto;
            max-width: 800px;
            border: 1px solid #ddd;
            border-radius: 8px;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .image {
            flex: 1;
            text-align: center;
        }

        .image img {
            max-width: 100%;
            border-radius: 8px;
        }

        .text {
            flex: 1;
            margin-left: 20px;
            text-align: justify;
        }

        /* Bảng */
        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            text-align: center;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
        }

        th {
            background-color: #f4f4f4;
        }

        /* Pano cuối trang */
        .footer {
            text-align: center;
            margin-top: 20px;
            padding: 20px;
            background-color: #f9f9f9;
        }

        .footer a {
            text-decoration: none;
            font-size: 18px;
            color: #007BFF;
        }

        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Pano đầu trang -->
    <div class="header">
        TRỌNG DUY
    </div>

    <!-- Khung giữa trang -->
    <div class="container">
        <div class="image">
            <img src="https://s.net.vn/0iSa" alt="Sample Image">
        </div>
        <div class="text">
            <p>
                Chào mọi người, mình là Duy. Hiện tại mình đang là 1 CBT-er, và mình đặc biệt yêu thích âm nhạc và vẽ vời, đam mê chạy bộ và thường có thời gian rảnh thì sẽ vừa chạy bộ vừa tận hưởng không khí trong lành của thiên nhiên. Ngoài ra, mình rất quan tâm đến Graphic designer, mình đang có ý định sẽ theo học ngành nghề đó trong tương lai. Hiện tại mình sẽ cố gắng hết mình để đạt được mục tiêu đầu tiên chính là vào được ngôi trường mà mình mơ ước. Trong cuộc sống, mình sẽ luôn cố gắng học hỏi, phát triển bản thân và chia sẻ những điều tích cực với mọi người xung quanh.
			
				</p>
        </div>
    </div>

    <!-- Bảng -->
    <table>
         <tr>
					<th>Ngày sinh</th>
                    <th>Chiều cao</th>
                    <th> Cân nặng</th>
                    <th>Số điện thoại</th>
                    <th>Email</th>
                    <th>Cung hoàng đạo</th>
                    <th>Nickname</th>
                    <th>Liên hệ facebook</th>
                </tr>
            </thead>
            <tbody>
                <!-- 2 hàng -->
                <tr>
					<td>24/07/2007 </td>
                    <td>1,73m </td>
                    <td>60 kg</td>
                    <td>0939764810</td>
                    <td>trongduyhotro2007@gmail.com</td>
                    <td>Sư Tử</td>
                    <td>YuD</td>
                    <td><a href="https://www.facebook.com/duy.trong.3975?locale=vi_VN"> Trần Trọng Duy </a></td>
                </tr>
    </table>

    <!-- Pano cuối trang -->
    <div class="footer">
        <a href="javascript:history.back()">Quay về trang trước</a>
    </div>

</body>
</html>
