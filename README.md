<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>Stingray</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #1A0B2E;
        color: #FFFFFF;
        margin: 0;
        padding: 0;
        text-align: center;
    }

    h1 {
        color: #9D6CFF;
        font-size: 3em;
        margin: 40px 0 10px 0;
    }

    p.description {
        font-size: 1.2em;
        max-width: 700px;
        margin: 0 auto 40px auto;
        line-height: 1.6;
    }

    .team-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
        padding-bottom: 40px;
    }

    .card {
        background-color: #2B1A4F;
        border-radius: 12px;
        width: 200px;
        padding: 20px;
        transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
        transform: translateY(-10px);
        box-shadow: 0 8px 20px rgba(0,0,0,0.5);
    }

    .card h3 {
        margin: 0 0 10px 0;
        color: #9D6CFF;
    }

    .card a img {
        margin-top: 10px;
        vertical-align: middle;
    }
</style>
</head>
<body>

<h1>Stingray</h1>
<p class="description">
Stingray é um projeto desenvolvido para a matéria de <strong>Programação Web 2</strong>, ministrado pelo professor Ronildo.
</p>

<h2>Equipe</h2>
<div class="team-container">
    <div class="card">
        <h3>Aladar Pinoti</h3>
        <a href="https://github.com/GuilhermeRodrigues2201" target="_blank">
            <img src="https://img.shields.io/badge/-Git-333333?style=flat&logo=github" alt="GitHub">
        </a>
    </div>
    <div class="card">
        <h3>Daniel Lopes</h3>
        <a href="https://github.com/GuilhermeRodrigues2201" target="_blank">
            <img src="https://img.shields.io/badge/-Git-333333?style=flat&logo=github" alt="GitHub">
        </a>
    </div>
    <div class="card">
        <h3>Guilherme Rodrigues</h3>
        <a href="https://github.com/GuilhermeRodrigues2201" target="_blank">
            <img src="https://img.shields.io/badge/-Git-333333?style=flat&logo=github" alt="GitHub">
        </a>
    </div>
    <div class="card">
        <h3>Gustavo Antônio</h3>
        <a href="https://github.com/GustavoLima3" target="_blank">
            <img src="https://img.shields.io/badge/-Git-333333?style=flat&logo=github" alt="GitHub">
        </a>
    </div>
</div>

</body>
</html>

