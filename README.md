<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color: aquamarine;
        }
        .out{
            font-family: 'Times New Roman', Times, serif;
            color: blue;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h2> Inline Handling </h2>
    <button onclick="showMessage()">Click Me</button>
    <p id="msg" class="out"></p>
    <script>
        function showMessage(){
            document.getElementById("msg").innerText="Button Clicked";
        }
    </script>
    
</body>
</html>
