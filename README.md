Index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Collaboration</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Hello, World!</h1>
    <p id="message">This is a simple collaborative project.</p>
    <button id="changeMessage">Click Me!</button>
    <script src="script.js"></script>
</body>
</html>


Style.css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 0;
    padding: 0;
    background-color: #eef;
}

h1 {
    color: #333;
}

button {
    margin-top: 20px;
    padding: 10px 15px;
    font-size: 16px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
button:hover {
    background-color: #0056b3;
}


Script.js
document.getElementById("changeMessage").addEventListener("click", function() {
    document.getElementById("message").textContent = "You clicked the button!";
});
