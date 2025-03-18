<!DOCTYPE html>
<html>
<head>
    <title>Dynamic Message</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; margin-top: 100px; }
        button { padding: 10px 20px; font-size: 16px; margin-top: 20px; cursor: pointer; }
        #message { font-size: 24px; font-weight: bold; color: #333; }
    </style>
</head>
<body>
    <h1 id="message">Hey! Click the button to see a message...</h1>
    <button onclick="changeMessage()">Click Me</button>

    <script>
        function changeMessage() {
            let messages = [
                "You are amazing! 😊",
                "Keep smiling, it suits you! 😁",
                "Believe in yourself! 💪",
                "Good things are coming your way! 🌟",
                "You're doing great! Keep going! 🚀"
            ];
            let randomIndex = Math.floor(Math.random() * messages.length);
            document.getElementById("message").innerText = messages[randomIndex];
        }
    </script>
</body>
</html>
