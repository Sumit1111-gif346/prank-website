<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hacked!</title>
    <style>
        body {
            background-color: black;
            color: red;
            font-family: "Courier New", Courier, monospace;
            text-align: center;
            padding-top: 20%;
            overflow: hidden;
        }
        h1 {
            font-size: 50px;
            text-shadow: 0 0 10px red, 0 0 20px red, 0 0 30px red;
            animation: glitch 1s infinite;
        }
        @keyframes glitch {
            0% { transform: translate(0); }
            20% { transform: translate(-2px, 2px); }
            40% { transform: translate(2px, -2px); }
            60% { transform: translate(-2px, -2px); }
            80% { transform: translate(2px, 2px); }
            100% { transform: translate(0); }
        }
    </style>
</head>
<body>
    <h1>Your Hacked!</h1>
    <p>Just kidding! Stay safe. 😄</p>
</body>
</html>
