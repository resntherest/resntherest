<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resty's Interactive Bio</title>
    <style>
        body {
            font-family: 'Courier New', monospace;
            background-color: #000000; /* Black background */
            color: #ffffff; /* White text */
            margin: 0;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }
        .container {
            max-width: 800px;
            text-align: center;
            background-color: #6424cc; /* Purple background for container */
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(100, 36, 204, 0.5);
        }
        .intro-greeting {
            font-size: 2em;
            line-height: 1.6;
            margin-bottom: 20px;
            overflow: hidden;
            white-space: nowrap;
            border-right: 2px solid #ffffff; /* White cursor */
            animation: typing 2s steps(25, end), blink-caret 0.75s step-end infinite;
            color: #ffffff; /* White text */
        }
        .intro-aspiration {
            font-size: 1.2em;
            line-height: 1.6;
            margin-bottom: 40px;
            color: #ffffff; /* White text */
        }
        @keyframes typing {
            from { width: 0; }
            to { width: 100%; }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent; }
            50% { border-color: #ffffff; } /* White blink */
        }
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
            background-color: #ffffff; /* White background for tech stack */
            padding: 20px;
            border-radius: 10px;
        }
        .tech-stack img {
            transition: transform 0.3s ease, filter 0.3s ease;
        }
        .tech-stack img:hover {
            transform: scale(1.1);
            filter: brightness(1.2);
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="intro-greeting">
            Hello, my name is Resty.
        </div>
        <div class="intro-aspiration">
            I aspire to work with data — whether Collecting it, Shaping it, Analyzing it, or Developing every possible way to let it speak for itself.
        </div>
        <!-- Tech Stack -->
        <div class="tech-stack">
            <img src="https://img.shields.io/badge/HTML-6424cc?style=for-the-badge&logo=html5&logoColor=6424cc&labelColor=000000&logoWidth=20" alt="HTML">
            <img src="https://img.shields.io/badge/CSS-000000?style=for-the-badge&logo=css3&logoColor=ffffff&labelColor=6424cc&logoWidth=20" alt="CSS">
            <img src="https://img.shields.io/badge/JS-6424cc?style=for-the-badge&logo=javascript&logoColor=6424cc&labelColor=000000&logoWidth=20" alt="JS">
            <img src="https://img.shields.io/badge/PY-000000?style=for-the-badge&logo=python&logoColor=ffffff&labelColor=6424cc&logoWidth=20" alt="PY">
            <img src="https://img.shields.io/badge/VB-6424cc?style=for-the-badge&logo=.net&logoColor=6424cc&labelColor=000000&logoWidth=20" alt="VB">
            <img src="https://img.shields.io/badge/%E2%96%A0-SQL-000000?style=for-the-badge&labelColor=6424cc" alt="SQL">
        </div>
    </div>
</body>
</html>
