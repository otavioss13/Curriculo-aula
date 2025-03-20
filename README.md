# Curriculo-aula

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Otavio Souza </title>
    <link rel="stylesheet" href="index.css">

</head>
<body>
    <div class="conteiner">
    <nav>
        <ul>
            <li>
                <a href="index.html"> Sobre mim</a>
            </li>
            <li>
                <a href="project.html"> Projeto </a>
            </li>
            <li>
                <a href="contact.html"> Contato </a>
            </li>
        </ul>
    </nav>

    <header>
        <div class="center">
            <img src="https://avatars.githubusercontent.com/u/202022602?v=4"></img>
        </div>
        <h1>Otavio Souza</h1>
        <h2> Desenvolverdor 🐓</h2>
    </header>

    <main>
        <section>
            <h3>Sobre mim </h3>
            <p>
                Otávio Santos de Souza, 18 anos cheio de lindeza. 
            </p>
        </section>
        <section>
            <h3>Formação </h3>
            <p>
                Formado em 2023 no ensino médio
                cursando a graduação de em sistemas da informção - UNIPLAC
            </p>
        </section>
        <section>
            <h3>Cursos </h3>
            <p>
                curso técnico - assistente administrativo - SENAI 
        
            </p>
        </section>
    </main>

    <footer>
        <a href="https://github.com/otavioss13" target="_blank" rel="noopener noreferrer">
            <img src="./img/git.png"></img>
            <p> github</p>
        </a>
        <a href="https://br.linkedin.com/" target="_blank" rel="noopener noreferrer">
            <img src="./img/linkedin.png"></img>
            <p> linkedin</p>
        </a>
        <a href="https://www.youtube.com/" target="_blank" rel="noopener noreferrer">
            <img src="./img/ytb.png"></img>
            <p> youtube</p>
        </a>

    </footer>
    </div>
</body>
</html>

body {
    color: white;
    background-color: black;   
    font-family: Arial, Helvetica, sans-serif;

}

ul {
    display: flex;
    justify-content: space-between;
    list-style-type: none;
    align-items: center;
    padding: 16px;

}

a{
    color:white;
    text-decoration: none;

}

header img{ 
    width: 150px;
    height: 170px;
    border-radius: 50%;
    border: 5px solid green;
}

.center {
    text-align: center;
}

h1{
    color: green;
}

footer img {
    width: 40px;
    height: 40px;
}

footer {
    display :flex;
    justify-content: center;
}

footer a {
    margin: 20px;
    text-align: center;
}

footer p {
    margin: 2px;
}

.conteiner {
    padding: 0px 50px;
}

nav a:hover {
    color: green;
}
