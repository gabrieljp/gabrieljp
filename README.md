<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Perfil GitHub</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="profile-container">
        <img src="seu-avatar.jpg" alt="Seu Avatar" class="avatar">
        <div class="profile-info">
            <h1>Seu Nome</h1>
            <h2>Sua Profissão/Interesse</h2>
            <p>Uma breve descrição sobre você. Quais tecnologias você usa, seus interesses em desenvolvimento, etc.</p>
            <ul class="social-links">
                <li><a href="https://github.com/seu-usuario" target="_blank">GitHub</a></li>
                <li><a href="https://linkedin.com/in/seu-linkedin" target="_blank">LinkedIn</a></li>
                <li><a href="https://twitter.com/seu-twitter" target="_blank">Twitter</a></li>
                </ul>
        </div>
    </div>
</body>
</html>

body {
    font-family: sans-serif;
    background-color: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
}

.profile-container {
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    padding: 30px;
    text-align: center;
}

.avatar {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 20px;
    border: 5px solid #ddd;
}

.profile-info h1 {
    margin-top: 0;
    color: #333;
}

.profile-info h2 {
    color: #777;
    margin-bottom: 15px;
}

.profile-info p {
    color: #555;
    line-height: 1.6;
    margin-bottom: 20px;
}

.social-links {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

.social-links a {
    text-decoration: none;
    color: #007bff;
    font-weight: bold;
    transition: color 0.3s ease;
}

.social-links a:hover {
    color: #0056b3;
}
