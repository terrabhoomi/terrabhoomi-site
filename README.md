# terrabhoomi-site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Terra Bhoomi | Welcome</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background: #f9f9f9; /* Premium light background */
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }

        .container {
            text-align: center;
        }

        .title {
            font-size: 2.5rem;
            font-weight: bold;
            margin-bottom: 1rem;
        }

        .subtitle {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }

        /* 3D Cube */
        .cube {
            width: 100px;
            height: 100px;
            position: relative;
            transform-style: preserve-3d;
            transform: rotateX(-30deg) rotateY(-45deg);
            animation: rotateCube 5s infinite linear;
        }

        .cube div {
            position: absolute;
            width: 100px;
            height: 100px;
            background: linear-gradient(145deg, #ffffff, #f1f1f1);
            border: 1px solid #ddd;
        }

        .cube .front {
            transform: translateZ(50px);
        }
        .cube .back {
            transform: rotateY(180deg) translateZ(50px);
        }
        .cube .right {
            transform: rotateY(90deg) translateZ(50px);
        }
        .cube .left {
            transform: rotateY(-90deg) translateZ(50px);
        }
        .cube .top {
            transform: rotateX(90deg) translateZ(50px);
        }
        .cube .bottom {
            transform: rotateX(-90deg) translateZ(50px);
        }

        @keyframes rotateCube {
            0% {
                transform: rotateX(-30deg) rotateY(-45deg);
            }
            100% {
                transform: rotateX(-30deg) rotateY(315deg);
            }
        }

        /* Button */
        .cta-button {
            display: inline-block;
            padding: 10px 20px;
            font-size: 1rem;
            color: #fff;
            background: #007BFF; /* Premium blue */
            border: none;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 2rem;
            transition: background 0.3s ease;
        }

        .cta-button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="title">Welcome to Terra Bhoomi</h1>
        <p class="subtitle">Experience the future of sustainable living.</p>
        <div class="cube">
            <div class="front"></div>
            <div class="back"></div>
            <div class="right"></div>
            <div class="left"></div>
            <div class="top"></div>
            <div class="bottom"></div>
        </div>
        <a href="#about" class="cta-button">Learn More</a>
    </div>
</body>
</html>