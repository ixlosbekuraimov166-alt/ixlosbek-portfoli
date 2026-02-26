<!DOCTYPE html>
<html>
<head>
    <title>Ixlosbek Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Ixlosbek</h1>
    <p>Kelajak Frontend Developer</p>
</header>

<main>
    <div class="card">
        <h3>Frontend</h3>
        <p id="text">Men HTML va CSS o‘rganayapman.</p>
        <button id="btn">Batafsil</button>
    </div>
</main>

<script src="script.js"></script>
</body>
</html>
body {
    background-color: #f2f2f2;
    text-align: center;
    font-family: Arial;
}

.card {
    background-color: white;
    width: 300px;
    margin: 20px auto;
    padding: 20px;
    border-radius: 12px;
    box-shadow: 0px 5px 15px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

button {
    background-color: darkblue;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
}
let button = document.getElementById("btn");
let text = document.getElementById("text");

button.addEventListener("click", function() {
    text.textContent = "Men endi JavaScript ham o‘rganayapman 🚀";
});
