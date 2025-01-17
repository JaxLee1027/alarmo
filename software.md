<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>System Diagram</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background: linear-gradient(to right, #c219f0, #6a11cb); 
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: white !important;
            text-shadow: none;
        }
        main {
            padding: 20px;
        }
        .diagram-container {
            text-align: center;
            margin: 20px 0;
        }
        .diagram-container img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            background: linear-gradient(to right, #6a11cb, #c219f0); /* 渐变颜色 */
            -webkit-background-clip: text; /* 让背景裁剪到文字区域 */
            -webkit-text-fill-color: transparent; /* 透明的文字填充色 */
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .section ul {
            margin: 0;
            padding-left: 20px;
        }
        .section ul li {
            margin-bottom: 10px;
        }
        .image-container {
            display: flex; /* 使用 Flexbox 布局让图片并排显示 */
            justify-content: center; /* 居中对齐图片 */
            gap: 10px; /* 图片之间的间距 */
        }
        .image-container img {
            width: 500px; /* 设置图片宽度一致 */
            height: auto; /* 高度根据宽度自动调整比例 */
            object-fit: cover; /* 确保图片填充且不变形 */
            border: 1px solid #ddd; /* 可选：为图片添加边框 */
            border-radius: 5px; /* 可选：为图片设置圆角 */
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
    </style>
</head>
<body>
    <header>
        <h1>Software Requirements Specification</h1>
    </header>
    <main>
        <div class="section">
            <h2>SRS 01 - The IMU 3-axis acceleration shall be measured with a 16-bit depth every 100 milliseconds ±10 milliseconds.</h2>
            <ul>
                <li><b>Abandoned</b> </li>
            </ul>
        </div>
        <div class="section">
            <h2>SRS 02 - System and alarm time switching function</h2>
            <ul>
                <li><b>Finished</b>
                    <ul>
                        <li>Users can switch between System and alarm time switching function.</li>
                        <li>The system shall allow users to switch between system time setting and alarm time setting modes.</li>
                    </ul>
                </li>
        <div class="image-container">
            <img src="button1.png" alt="lcd1">
        </div>
            </ul>
        </div>
        <div class="section">
            <h2>SRS 03 - Motor control and timing logic</h2>
            <ul>
                <li><b>Finished</b>
                    <ul>
                        <li>The motor activates.</li>
                    </ul>
                    <ul>
                        <li>The motor begins moving away from the user as the alarm time approaches.</li>
                    </ul>
                    <img src="motorcode.png" alt="lcd2">
            </ul>
        </div>
                <div class="section">
            <h2>SRS 04 - Distance sensing functionality</h2>
            <ul>
                <li><b>Finished</b>
                    <ul>
                        <li>The system detects obstacles.</li>
                    </ul>
                    <ul>
                        <li>The system adjusts its movement path to avoid collisions.</li>
                    </ul>
                    <img src="distance.png" alt="lcd2">
            </ul>
        </div>
                <div class="section">
            <h2>SRS 05 - User interface control</h2>
            <ul>
                <li><b>Finished</b>
                    <ul>
                        <li>The system is equipped with buttons for setting time, switching modes, and resetting the system.</li>
                    </ul>
                    <img src="button2.png" alt="lcd2">
            </ul>
        </div>
                <div class="section">
            <h2>SRS 06 - Low power management</h2>
            <ul>
                <li><b>Abandoned</b>
                    <ul>
                        <li>When the display and movement system are not in use, the device shall enter low power mode to conserve energy.
                        </li>
                    </ul>
            </ul>
        </div>
        </div>
                <div class="section">
            <h2>SRS 07 - Real Time Clock</h2>
            <ul>
                <li><b>Finished</b>
                    <ul>
                        <li>The RTC module ensures precise timekeeping and accurate alarm scheduling.</li>
                    </ul>
                <img src="RTC_proof.png" alt="System Diagram">
            </ul>
        </div>
        <a href="index.html">Back to home page</a>
    </main>
    <footer>
        <p>Copyrights reserved.</p>
    </footer>
</body>
</html>
