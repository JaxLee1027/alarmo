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
        <h1>System Diagram</h1>
    </header>
    <main>
        <div class="diagram-container">
            <img src="systemdiagram.png" alt="System Diagram">
        </div>
        <div class="section">
            <h2>Input Components</h2>
            <ul>
                <li><b>Distance Sensor:</b> Detects obstacles within a range of 30 cm and enables path adjustment.</li>
                <li><b>Buttons:</b> Allow users to set the time, change modes, and reset the system.</li>
            </ul>
        </div>
        <div class="section">
            <h2>Micro controller</h2>
            <ul>
                <li><b>ATmega328PB Module:</b>
                    <ul>
                        <li>Central processing and control unit.</li>
                        <li>Communicate between input components and output components.</li>
                    </ul>
                </li>
                <li><b>RTC module:</b>
                    <ul>
                        <li>Ensure precise timekeeping and accurate alarm scheduling.</li>
                    </ul>
                </li>
            </ul>
        </div>
        <div class="section">
            <h2>Output Components</h2>
            <ul>
                <li><b>Motors and Wheels:</b>
                    <ul>
                        <li>TT motors controlled via a motor driver to enable movement.</li>
                    </ul>
                </li>
                <li><b>Motor Driver:</b>
                    <ul>
                        <li> Control motors to move forward and turn, limit current output.</li>
                    </ul>
                </li>
                <li><b>Speaker:</b>
                    <ul>
                        <li>Emits a "Little Star" at ~80 dB to wake the user.</li>
                    </ul>
                </li>
                <li><b>LCD Display:</b>
                    <ul>
                        <li>Displays the system time, alarm time, status, and animated emoticons.</li>
                    </ul>
                </li>
                <li><b>LED Indicator:</b>
                    <ul>
                        <li>Displays system status, particularly when the LCD is off, to save battery.</li>
                    </ul>
                </li>
            </ul>
        </div>
        <a href="index.html">Back to home page</a>
    </main>
    <footer>
        <p>Copyrights reserved.</p>
    </footer>
</body>
</html>
