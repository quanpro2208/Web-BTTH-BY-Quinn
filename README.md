<!DOCTYPE html>
<html lang="vi">
<head>
    <title>BTTH</title>
</head>
<body>
    <div class="section audio-container">
    <h1>Bài Tập Thực Hành</h1>
      </div>

    <div class="section flex-container">
        <div class="flex-item">
            <h2>Ảnh cá nhân</h2>
            <img src="tư liệu/anhcanhan.jpg" alt="Ảnh cá nhân">
        </div>
        <div class="flex-item">
            <h2>Tóm tắt tiểu sử</h2>
            <ul>
                <li><strong>Họ và tên:</strong> Võ Ngọc Quân</li>
                <li><strong>Ngày sinh:</strong> 22/8/2007</li>
                <li><strong>Quê quán:</strong> Quảng Trị</li>
                <li><strong>Chỗ ở:</strong> Đông Lương</li>
                <li><strong>Lớp:</strong> 12A2</li>
                <li><strong>Trường:</strong> THPT Lê Lợi</li>
                <li><strong>Sở thích:</strong> Code, Âm Nhạc</li>
            </ul>
        </div>
        <div class="flex-item">
            <h2>Giới thiệu bản thân</h2>
            <p>Tôi là Võ Ngọc Quân, học sinh lớp 12A2 tại THPT Lê Lợi. Tôi yêu thích lập trình và âm nhạc.</p>
        </div>
    </div>

    <div class="section flex-container">
        <div class="flex-item">
            <h2>Địa chỉ các trang web</h2>
            <ul>
                <li><a href="https://short.com.vn/MIH4" target="_blank">Facebook</a></li>
                <li><a href="https://thptleloi.quangtri.edu.vn/" target="_blank">Trường THPT Lê Lợi</a></li>
                <li><a href="https://thptleloi.quangtri.edu.vn/gioi-thieu/ban-gia-m-hie-u" target="_blank">BGH Trường THPT Lê Lợi</a></li>
                <li><a href="https://thptleloi.quangtri.edu.vn/trang-chu/tho-i-kho-a-bie-u" target="_blank">TKB Lê Lợi</a></li>
                <li><a href="https://quangtri.edu.vn/" target="_blank">Sở GD&ĐT Quảng Trị</a></li>
            </ul>
        </div>
        <div class="flex-item">
            <h2>Các bài tập</h2>
            <ul>
                <li><a href="dữ liệu/bài 1.html" >Bài 1</a></li>
                <li><a href="dữ liệu/bài 2.html" >Bài 2</a></li>
                <li><a href="dữ liệu/bài 3.html" >Bài 3</a></li>
                <li><a href="dữ liệu/bài 4.html" >Bài 4</a></li>
                <li><a href="dữ liệu/bài 5.html" >Bài 5</a></li>
            </ul>
        </div>
    </div>

    <div class="section video-continer">
        <h2>Video</h2>
        <video controls>
            <source src="tư liệu/video.mp4" type="video/mp4">
            Trình duyệt của bạn không hỗ trợ phát video.
        </video>
    </div>
  
      <div class="section audio-container">
        <h2>Audio</h2>
      <!--thêm <audio src="tiny love.mp3" autoplay></audio> để tự động phát khi tải trang -->
        <audio controls>
            <source src="tư liệu/tiny love.mp3" type="audio/mpeg">
            Trình duyệt của bạn không hỗ trợ phát âm thanh.
        </audio>
    </div>

    <div class="section iframe-container">
    <div class="iframe-item">
        <h2>Khung tuyệt đối</h2>
        <iframe src="https://thptleloi.quangtri.edu.vn/gioi-thieu/thanh-tich-nha-truong" height="300"></iframe>
    </div>
    <div class="iframe-item">
        <h2>Khung tương đối</h2>
        <iframe src="dữ liệu\Khung tương đối.html" height="300"></iframe>
    </div>
</div>
<div class="section">
    <button onclick="scrollToTop()" class="back-to-top">Quay lại trang đầu</button>
</div>
<!-- Javascript -->
<script>
    function scrollToTop() {
        window.scrollTo({ top: 0, behavior: 'smooth' });
    }
</script>
<!-- CSS -->
<style>
    /* Vùng chứa cho các phần iframe */
    .iframe-container {
        display: flex;
        gap: 20px;
        justify-content: space-between;
        align-items: flex-start;
    }

    /* Kiểu cho từng vùng chứa iframe */
    .iframe-item {
        flex: 1;
        border-radius: 10px;
        border: 2px solid #ddd;
        padding: 10px;
        background-color: #fff;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        transition: 0.3s;
    }

    /* Hiệu ứng di chuột cho vùng chứa */
    .iframe-item:hover {
        transform: scale(1.05);
        box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
    }

    iframe {
        width: 100%;
        border-radius: 10px;
    }

    /* Đảm bảo iframe có cùng chiều cao */
    iframe {
        height: 300px;
    }
</style>

  
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0 auto;
            max-width: 1200px;
            background: linear-gradient(to bottom right, #6a8d92, #b0c9d1, #a8c0e8);
            background-size: 300% 300%;
            animation: backgroundAnimation 5s ease infinite;
            color: #333;
            line-height: 1.6;
        }
        h1 {
            text-align: center;
            margin: 20px 0;
            text-transform: uppercase;
            color: #1c3c61;
            animation: fadeIn 2s;
        }
      h2 {
            text-align: center;
            margin: 20px 0;
            text-transform: uppercase;
            color: #1c3c61;
        }
        a {
            text-decoration: none;
            color: #4a90e2;
            transition: 0.3s;
        }
        a:hover { 
            color: #ff8c42; 
            transform: scale(1.1); 
            text-shadow: 0 0 10px rgba(255, 140, 66, 0.8);
            animation: glow 1s infinite alternate;
        }
        img, iframe, audio, video {
            border-radius: 10px;
            border: 2px solid #ddd;
            transition: 0.3s;
            width: 100%;
        }
        img:hover, iframe:hover, audio:hover, video:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        .section {
            margin: 20px 0;
            padding: 15px;
            background: #fff;
            border: 2px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            animation: slideIn 1s;
        }
        .flex-container {
            display: flex;
            gap: 20px;
            justify-content: space-between;
        }
        .flex-item { flex: 1; }
        ul { padding-left: 20px; }
        .media-container, .iframe-container { display: flex; gap: 20px; }
          .back-to-top {
        display: block;
        margin: 0 auto;
        padding: 10px 20px;
        font-size: 16px;
        color: #fff;
        background-color: #4a90e2;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        transition: 0.3s;
    }
    .back-to-top:hover {
        background-color: #ff8c42;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        transform: scale(1.1);
    }

        /* Hiệu ứng */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateX(-50%); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
        @keyframes glow {
            0% { box-shadow: 0 0 5px #ff8c42, 0 0 15px #ff8c42; }
            50% { box-shadow: 0 0 15px #ff8c42, 0 0 30px #ff8c42; }
            100% { box-shadow: 0 0 5px #ff8c42, 0 0 15px #ff8c42; }
        }
        @keyframes backgroundAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
    </style>
</body>
</html>
