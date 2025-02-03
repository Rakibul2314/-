<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Secret Message for You!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(45deg, #ff758c, #ff7eb3);
            color: white;
            padding: 50px;
        }
        .message-box {
            display: none;
            font-size: 24px;
            font-weight: bold;
            background: white;
            color: black;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.3);
            animation: fadeIn 2s ease-in-out;
        }
        button {
            padding: 15px 30px;
            font-size: 18px;
            font-weight: bold;
            background: #ff4757;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            transition: 0.3s;
        }
        button:hover {
            background: #ff6b81;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }
    </style>
</head>
<body>

    <h1>👀 Click Below for a Surprise! 🎁</h1>
    <button onclick="showMessage()">Click Me!</button>
    <div id="message" class="message-box">
        🎉 Surprise! You are an amazing friend! 😍 Keep smiling! 😊
    </div>

    <script>
        function showMessage() {
            document.getElementById("message").style.display = "block";
        }
    </script>

</body>
</html># -
সবার জন্য শুভেচ্ছা
