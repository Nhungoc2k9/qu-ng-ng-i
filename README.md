# đặc sản quảng ngãi

<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đặc Sản Quảng Ngãi</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #fffaf0;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #a83232, #e67e22);
            color: white;
            text-align: center;
            padding: 45px 20px;
        }

        header h1 {
            font-size: 38px;
            margin-bottom: 15px;
        }

        header p {
            font-size: 18px;
        }

        nav {
            background: #7d2525;
            text-align: center;
            padding: 15px;
            position: sticky;
            top: 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffd700;
        }

        .banner {
            text-align: center;
            padding: 35px 20px;
        }

        .banner h2 {
            color: #a83232;
            margin-bottom: 15px;
            font-size: 28px;
        }

        .container {
            max-width: 1150px;
            margin: auto;
            padding: 20px;
        }

        .food-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
        }

        .food-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 12px #0002;
            transition: 0.3s;
        }

        .food-card:hover {
            transform: translateY(-7px);
        }

        .food-card img {
            width: 100%;
            height: 210px;
            object-fit: cover;
        }

        .food-card .content {
            padding: 18px;
        }

        .food-card h3 {
            color: #a83232;
            margin-bottom: 12px;
        }

        .food-card p {
            line-height: 1.6;
            margin-bottom: 15px;
        }

        .food-card a {
            display: inline-block;
            background: #c0392b;
            color: white;
            padding: 9px 15px;
            text-decoration: none;
            border-radius: 6px;
        }

        .food-card a:hover {
            background: #e67e22;
        }

        .about {
            background: #fbe5c8;
            padding: 40px 20px;
            margin-top: 40px;
            text-align: center;
        }

        .about h2 {
            color: #a83232;
            margin-bottom: 18px;
        }

        .about p {
            max-width: 850px;
            margin: auto;
            line-height: 1.8;
            font-size: 17px;
        }

        footer {
            background: #7d2525;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 30px;
            line-height: 1.8;
        }

        @media(max-width: 600px) {
            header h1 {
                font-size: 27px;
            }

            nav a {
                display: inline-block;
                margin: 7px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1> ĐẶC SẢN QUẢNG NGÃI </h1>
    <p>Khám phá hương vị quê hương núi Ấn - sông Trà</p>
</header>

<nav>
    <a href="#home">Trang chủ</a>
    <a href="#monan">Món ăn</a>
    <a href="#gioithieu">Giới thiệu</a>
    <a href="#lienhe">Liên hệ</a>
</nav>

<section class="banner" id="home">
    <h2>Ẩm thực quê hương Quảng Ngãi</h2>
    <p>
        Quảng Ngãi không chỉ nổi tiếng với cảnh đẹp thiên nhiên
        mà còn hấp dẫn bởi những món ăn dân dã, đậm đà hương vị miền Trung.
    </p>
</section>

<div class="container" id="monan">

    <div class="food-list">

        <div class="food-card">
            <img src="https://mia.vn/media/uploads/blog-du-lich/canh-don-quang-ngai-1714667049.jpg"
                 alt="Món don Quảng Ngãi">
            <div class="content">
                <h3>1. Don Quảng Ngãi</h3>
                <p>
                    Don là món ăn dân dã nổi tiếng của Quảng Ngãi.
                    Don được nấu cùng nước dùng thanh ngọt, ăn kèm
                    bánh tráng nướng và hành lá.
                </p>
                <a href="https://laodong.vn/du-lich/kham-pha/don-dac-san-dan-da-dam-da-tinh-que-quang-ngai-1191108.html"
                   target="_blank">Tìm hiểu thêm</a>
            </div>
        </div>

        <div class="food-card">
            <img src="https://media-cdn-v2.laodong.vn/storage/newsportal/2026/4/7/1681412/CA-BONG.jpg"
                 alt="Cá bống kho tiêu">
            <div class="content">
                <h3>2. Cá bống sông Trà</h3>
                <p>
                    Cá bống sông Trà kho tiêu là món ăn đặc trưng,
                    có vị mặn ngọt hài hòa, cay nhẹ và thơm ngon,
                    thường được ăn cùng cơm nóng.
                </p>
                <a href="https://laodong.vn/du-lich/am-thuc/ca-bong-song-tra-dac-san-dua-com-cua-nguoi-quang-ngai-1681412.html"
                   target="_blank">Tìm hiểu thêm</a>
            </div>
        </div>

        <div class="food-card">
            <img src="https://media3.baotintuc.vn/images/XtMI2cTUOu7JtJPwFuYGlCeHKThqJyEonOiRlOvhu2SDy317wXrfpGcbiMHYhjqV1YIIHso5IilaWB_cR_wtle78brhmbefMP7w9jZfMdRA/ec0a8e9136aca8bce732df294ffd204b-1.jpg.avif"
                 alt="Ram bắp">
            <div class="content">
                <h3>3. Ram bắp</h3>
                <p>
                    Ram bắp được làm từ bắp non bào nhỏ, trộn gia vị,
                    cuốn bánh tráng rồi chiên vàng giòn.
                    Món ăn có vị ngọt tự nhiên của bắp.
                </p>
                <a href=https://dantocmiennui.baotintuc.vn/doc-dao-mon-ram-bap-cua-nguoi-quang-ngai-post1325979.html
                   target="_blank">Tìm hiểu thêm</a>
            </div>
        </div>

        <div class="food-card">
            <img src="https://media-cdn-v2.laodong.vn/storage/newsportal/2026/3/14/1669091/Rsz_569820283_157460.jpg"
                 alt="Bánh xèo">
            <div class="content">
                <h3>4. Bánh xèo Quảng Ngãi</h3>
                <p>
                    Bánh xèo có lớp vỏ vàng giòn, nhân tôm thịt
                    thơm ngon, ăn kèm rau sống và nước chấm đậm đà.
                </p>
                <a href="https://laodong.vn/du-lich/am-thuc/quan-banh-xeo-chuan-vi-quang-ngai-giua-long-ha-noi-1669091.html"
                   target="_blank">Tìm hiểu thêm</a>
            </div>
        </div>

        <div class="food-card">
            <img src="https://scov.gov.vn/upload/2005660/20210923/fef622e50589cadf322690172779abb420160531%5C095218_8.jpg"
                 alt="Kẹo gương">
            <div class="content">
                <h3>5. Kẹo gương</h3>
                <p>
                    Kẹo gương là đặc sản nổi tiếng với lớp kẹo
                    mỏng, trong như gương, có vị ngọt và thơm
                    của đậu phộng, mè rang.
                </p>
                <a href="https://scov.gov.vn/ban-sac-van-hoa/huong-vi-que-nha/keo-guong-quang-ngai.html"
                   target="_blank">Tìm hiểu thêm</a>
            </div>
        </div>

        <div class="food-card">
            <img src="https://lalago.vn/wp-content/uploads/2025/06/Banh-bo-Quang-Ngai-5-1024x741.jpg"
                 alt="Bánh bó">
            <div class="content">
                <h3>6. Bánh bó Quảng Ngãi</h3>
                <p>
                    Bánh bó là món bánh truyền thống được làm từ
                    bột nếp và các loại nguyên liệu như gừng,
                    chuối, đậu phộng, tạo nên hương vị thơm ngon.
                </p>
                <a href="https://lalago.vn/banh-bo-quang-ngai/"
                   target="_blank">Tìm hiểu thêm</a>
            </div>
        </div>

    </div>
</div>

<section class="about" id="gioithieu">
    <h2>Nét đẹp ẩm thực Quảng Ngãi</h2>
    <p>
        Ẩm thực Quảng Ngãi mang đậm nét bình dị, mộc mạc
        của con người miền Trung. Mỗi món ăn đều chứa đựng
        những câu chuyện văn hóa và truyền thống của quê hương.
        Những hương vị đặc trưng ấy không chỉ làm say lòng
        người dân địa phương mà còn để lại ấn tượng sâu sắc
        đối với du khách khi đến với Quảng Ngãi.
        Hãy một lần thưởng thức để cảm nhận trọn vẹn
        hương vị quê hương núi Ấn - sông Trà!
    </p>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/PbAMVNLkHeQ" title="Quang Ngai Specialties | Top 16 Must-Try Local Delicacies in Quang Ngai!" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    
  
</section>

<footer id="lienhe">
    <h3>QUẢNG NGÃI - QUÊ HƯƠNG YÊU DẤU</h3>
    <p>Website giới thiệu văn hóa ẩm thực Quảng Ngãi</p>
    <p>© 2026 - Giới thiệu đặc sản quê hương</p>
</footer>

</body>
</html>
