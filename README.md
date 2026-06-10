<!DOCTYPE html>
<html>
<head>
    <title>Interactive Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 100px;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
        }
    </style>
</head>
<body>

    <h1 id="message">Hello!</h1>

    <button onclick="changeText()">Click Me</button>

    <script>
        function changeText() {
            document.getElementById("message").innerText = "You clicked the button!";
        }
    </script>

</body>
</html>
