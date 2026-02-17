<!DOCTYPE html>
<html lang="vi">
<head>              
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello các em</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f9f9f9;
        }

        .header-title {
            text-align: center;
            color: #d9534f; 
            font-size: 24px;
            font-weight: bold;
            border-bottom: 1px solid #ccc;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        .intro-text {
            font-weight: bold;
            margin-bottom: 20px;
            text-align: center;
        }

        .container {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            gap: 20px; 
            flex-wrap: wrap; 
        }

        .column-image {
            flex: 1;
            min-width: 250px;
        }
        .column-image img {
            width: 100%;
            height: auto;
            border: 1px solid #ddd;
        }

       
        .column-text {
            flex: 1.5; 
            min-width: 250px;
            padding: 0 10px;
        }

        .info-box {
            border: 1px solid #555;
            padding: 10px 15px;
            margin-bottom: 15px;
            font-size: 20px;
            color: #333;
            text-align: left;
            background-color: #fff;
        }

        .column-video {
            flex: 1;
            min-width: 250px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
     <a href="huybui.html">Quang Huy</a>
    <a href="nhathoang.html">Nhật Hoàng</a>
    <a href="trungnguyen.html">Trung Nguyên</a>
    <a href="uyennhi.html">Uyển Nhi</a>
    

    <div class="header-title">Welcome</div>

    <div class="intro-text">Xin tự giới thiệu bản thân tôi :</div>

    <div class="container">
        <div class="column-image">
            <img src="anhhuy.mp4.jfif" alt="Ảnh cá nhân">
        </div>

        <div class="column-text">
            <div class="info-box">Họ và tên : Bùi Quang Huy </div>
            <div class="info-box">Ngày sinh : 03/04/2008</div>
            <div class="info-box">Đang học tại : Trường THPT Phan Đăng Lưu</div>
            <div class="info-box">Lớp : 12A6</div>
            <div class="info-box">Sở thích : Thủ môn bóng đá</div>
            <div class="info-box">Nghành học yêu thích : Sư Phạm Tin Học</div>
            <div class="info-box">Ước mơ : Gia đình hạnh phúc, ấm no sum vầy</div>
        </div>

        <div class="column-video">
            <video src="huyhuyhuy.mp4" controls width="80%"></video>
        </div>
    </div>

</body>
</html>
