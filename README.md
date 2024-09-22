# Topsecret2
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Style.css">
    <link rel="stylesheet" href="Reset.css">
    <title>Novos Estilos</title>
</head>
<sctyle>

  body {
    background-image: url(https://i.pinimg.com/originals/d2/27/82/d227823a2ed8fbfecdd8258f250e9b5b.gif);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}

footer {
    text-align: center;
    background-color: black;
    color: white;
}

.Menu {
    margin: auto;
    padding: auto;
    text-align: center;
    text-shadow: 1px 1px white;
    animation: infinite;
    font-size: 80px;
}

.container {
    margin: 30px;
    display: flex;
    justify-content: space-evenly;
    align-items: center;

}

.container2 {
    margin: 30px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.item img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 210px;
    max-height: 150px;
    max-width: 100%;
}

.item {
    min-width: 0;
    margin: 1px;
    transition: 0.8s ease;
    box-shadow: 5px 5px 10px 2px #cccccc;
    border-radius: 10px;
}

.item:hover {
    transform: scale(0.9);
}

.blockquote {
    font-style: italic;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1.5rem;
    color: #cccccc;
    text-align: center;

}

        
</sctyle>

<!-- Menu -->
<div class="Menu">
    <h3>Clicar a imagem</h3>
</div>
<!-- Fim Menu -->

<body>
    <div class="container">
        <div class="item">
            <a href="estilo 1/Index1.html">
                <img
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsyUPgYuJ5tMlotD8E5VlU9eDeagaS8-V89tzhMrg3cna5ic-qNrGSssseyqBiYFSUAqI&usqp=CAU" />
            </a>
        </div>
        <div class="item">
            <a href="/estilo 2/Index1.html">
                <img
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsyUPgYuJ5tMlotD8E5VlU9eDeagaS8-V89tzhMrg3cna5ic-qNrGSssseyqBiYFSUAqI&usqp=CAU" />
            </a>
        </div>
    </div>
    <div class="container">
        <div class="item">
            <a href="/estilo 3/Index1.html">
                <img
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsyUPgYuJ5tMlotD8E5VlU9eDeagaS8-V89tzhMrg3cna5ic-qNrGSssseyqBiYFSUAqI&usqp=CAU" />
            </a>
        </div>
        <div class="item">
            <a href="https://github.com/wysley23">
                <img
                    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRDdraOP0lSWd9prQnS7x7Rk3Gm18vMZltYpw&s" />
            </a>
        </div>
    </div>

    <footer>
        <nav>
            <blockquote class="blockquote">
                <p>A Criacao do site. &copy</p>
                <p>Wysley</p>
                <p>Todos os direitos reservados &copy; 2024 - GITHUB</p>
                <p>Contato: 83 9999-9999</p>
            </blockquote>
        </nav>
    </footer>

</body>

</html>
