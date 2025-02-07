<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Love </title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #ffe6e6;
            margin: 0;
            padding: 50px;
        }
        h1 {
            color: #d63384;
        }
        p {
            font-size: 18px;
            color: #444;
        }
        .button-container {
            margin-top: 30px;
        }
        .btn {
            padding: 15px 25px;
            font-size: 20px;
            color: white;
            background-color: #ff4d6d;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #e60040;
        }
    </style>
</head>
<body>
    <h1>My Love </h1>
    <p>From the moment I met you, my world changed. You are the most beautiful part of my life.</p>
    <p>I can't imagine my future without you in it.</p>
    <p>Will you make me the happiest person and marry me?</p>
    
    <div class="button-container">
        <button class="btn" onclick="sayYes()"> Yes, I Will! </button>
    </div>

    <script>
        function sayYes() {
            alert("You just made me the happiest person!");
        }
    </script>
</body>
</html>
