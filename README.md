<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
        }
        h1 {
            color: #333;
        }
        .button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            background-color: lightgray;
        }
    </style>
</head>

<body>

    <!-- Logo -->
    <img src="logo.png" alt="Multiple Ideas Logo" style="width:150px;">

    <h1>Hi, I'm [Your Name]!</h1>
    <p>I’m a middle school student learning tech, coding, and business.</p>

    <h2>My Projects</h2>
    <ul>
        <li>Project 1: (add something you made)</li>
        <li>Project 2: (add another idea)</li>
    </ul>

    <h2>Business Ideas</h2>
    <p>Here are ideas I might turn into a real business someday:</p>
    <ul>
        <li>Build websites</li>
        <li>Make apps or games</li>
        <li>Sell digital products</li>
    </ul>

    <h2>Interactive Button</h2>
    <p>Click the button and watch the number go up:</p>

    <button class="button" onclick="increaseCount()">Click Me</button>
    <p>You clicked: <span id="count">0</span> times</p>

    <script>
        let count = 0;
        function increaseCount() {
            count++;
            document.getElementById("count").innerText = count;
        }
    </script>

</body>
</html>