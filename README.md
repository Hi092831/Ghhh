# Ghhh<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>กดหาพ่อมึงหรอ</title>
    <style>
        button {
            font-size: 20px;
            padding: 10px 20px;
            cursor: pointer;
        }
        #message {
            font-size: 24px;
            margin-top: 20px;
            color: blue;
        }
    </style>
</head>
<body>
    <button onclick="showMessage()">กดที่นี่</button>
    <p id="message"></p>

    <script>
        function showMessage() {
            document.getElementById('message').innerText = 'กดหาบิดาหรอ';
        }
    </script>
</body>
</html>
