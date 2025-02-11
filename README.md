<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
        }
        h1 {
            color: #007BFF;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #28a745;
            color: white;
            border: none;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p id="message">Click the button to see magic!</p>
    <button onclick="changeText()">Click Me!</button>
    
    <script>
        function changeText() {
            document.getElementById("message").innerText = "Hello, thanks for visiting!";
        }
    </script>
</body>
</html>
