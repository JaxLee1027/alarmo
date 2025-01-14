<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazing Alarmo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }
        header {
            background: linear-gradient(to right, #c219f0, #6a11cb); 
            color: white;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            color: white !important;
            text-shadow: none;
        }
        .content {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            text-align: center; /* 让标题居中 */
        }
        .content img {
            max-width: 100%;
            height: auto;
        }
        .content video {
            max-width: 100%;
            height: auto;
        }
        footer {
            background: linear-gradient(to right, #6a11cb, #c219f0); /* 渐变从蓝紫色到紫色 */
            color: white; /* 设置文字为白色 */
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            text-align: center;
        }
        a {
            color: #008cba;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            text-decoration: underline;
        }
        /* 描述文字左对齐 */
        .description {
            text-align: left;
            color: #555555;
            line-height: 1.6;
        }
        .more-info a {
            background: linear-gradient(to right, #6a11cb, #c219f0); /* 渐变颜色 */
            -webkit-background-clip: text; /* 让背景裁剪到文字区域 */
            -webkit-text-fill-color: transparent; /* 透明的文字填充色 */
            text-decoration: none; /* 去掉下划线 */
            font-weight: bold; /* 字体加粗（可选） */
        }
        .more-info a:hover {
            text-decoration: underline; /* 鼠标悬停时加下划线 */
        }
    </style>
</head>
    <body>
        <header>
            <h1>Amazing Alarmo</h1>
            <p>University of Pennsylvania, ESE 5190</p>
            <p>Team: Hugging Overflow</p>
            <p>Member: Jiayang Li, Peng Su, Yuhe Zhang</p>
        </header>
    <div class="content">
        <h2>Product Review</h2>
        <p class="description">
            Alarmo is an innovative mobile alarm clock designed to help students who struggle to wake up early. Traditional alarms are limited by their fixed position: if placed near the bed, they’re too easy to turn off and fall back asleep; if placed farther away, they become inconvenient to set up each night. This mobile alarm clock effectively addresses both issues. Users can conveniently set it up bedside before sleep, and when it goes off in the morning, it automatically moves to the other side of the room, forcing the user to get out of bed and turn it off. This approach combines ease of setup with an effective way to prevent oversleeping.
        </p>
        <img src="alarmo1.png" alt="Alarmo">
        <div class="video">
            <h2>Demonstration Video</h2>
            <iframe src="https://drive.google.com/file/d/1WSwifaCDaiMutOcksjoA3FaBC6sSkugz/preview" allow="autoplay" width="640" height="360"></iframe>
        </div>
        If the video doesn't play, use this link:
        <a href="https://drive.google.com/file/d/1WSwifaCDaiMutOcksjoA3FaBC6sSkugz/view?usp=sharing">Demo</a>
    </div>
    <div class="content">
        <h2>More Information</h2>
        <p class="more-info">
            <a href="system.html">System Diagram</a> |
            <a href="software.html">Software Requirements Specification</a> |
            <a href="hardware.html">Hardware Requirements Specification</a>
        </p>
    </div>
    <footer>
        <p>Copyrights reserved.</p>
    </footer>
</body>
</html>
