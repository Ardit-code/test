<!DOCTYPE html>
<html lang="sq">
<head>
    <meta charset="UTF-8">
    <title>Faqja ime</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Mirësevini në faqen time</h1>
        <p>Kjo faqe është publikuar me GitHub Pages 🚀</p>
    </header>

    <section class="card">
        <h2>Rreth meje</h2>
        <p>Unë jam Ardit dhe po mësoj programim.</p>
        <button onclick="alert('Bravo Ardit 🔥')">Kliko këtu</button>
    </section>

</body>
</html>


body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #1e3c72, #2a5298);
    color: white;
    text-align: center;
}

header {
    padding: 50px;
}

.card {
    background: rgba(255, 255, 255, 0.1);
    padding: 30px;
    margin: 50px auto;
    width: 300px;
    border-radius: 15px;
    backdrop-filter: blur(10px);
}

button {
    padding: 10px 20px;
    border: none;
    border-radius: 10px;
    background: #00c6ff;
    color: white;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background: #0072ff;
    transform: scale(1.1);
}




