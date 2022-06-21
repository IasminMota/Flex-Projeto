# Flex-Projeto

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flex Turismos</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <header>
	<div class="flex-container menu">
        <h1>FlexTurismos</h1>
        <ul class="flex-container list-itens>
            <li><a href="#quem-somos">Quem Somos</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#planos">Planos</a></li>
			</div>
        </ul>
    </header>
    <div>
        <div>
            <h1>Flex <br>Turismos</h1>
            <p>O melhor serviço para você!</p>
            <a href="">Saiba Mais!</a>
        </div>

        <div>
            <div><img src="0-main.png" alt="banner de apresentação"></div>
        </div>
    </div>

    <div>
        <div>
            <img src="1-quem-somos.png" alt="balcão de atendimento">
        </div>

        <div>
            <h2>Quem somos</h2>
            <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. </p>
            <p>The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English.</p>
        </div>
    </div>

    <div>
        <div>
            <h2>Serviços</h2>
        </div>

        <div>
            <div>
                <div><img src="icon-2.png" alt="hospedagens"></div>
                <p>Hospedagens</p>
                <a href="#">Comprar Agora</a>
            </div>

            <div>
               <div><img src="icon-1.png" alt="pacote de viagens"></div>
               <p>Pacotes de viagens</p>
               <a href="#">Comprar Agora</a>
            </div>

            <div>
                <div><img src="icon-3.png" alt="roteiros personalizados"></div>
                <p>Roteiros personalizados</p>
                <a href="#">Comprar Agora</a>
            </div>

        </div>
    </div>

    <div>

        <div>
            <h3>Plano 2</h3>
            <ul>
                <li>Suporte 24h</li>
                <li>Serviços de quarto</li>
                <li>Guia turístico</li>
            </ul>
            <a href="#">Saiba Mais!</a>
        </div>

        <div>
            <h3>Plano 2</h3>
            <ul>
                <li>Suporte 24h</li>
                <li>Serviços de quarto</li>
                <li>Guia turístico</li>
                <li>Roteiro de trilhas</li>
                <li>Serviço personalizado</li>
            </ul>
            <a href="#">Saiba Mais!</a>
        </div>

        <div>
            <h3>Plano 3</h3>
            <ul>
                <li>Suporte 24h</li>
                <li>Serviços de quarto</li>
                <li>Guia turístico</li>
                <li>Roteiro de trilhas</li>
                <li>Serviço personalizado</li>
                <li>Área Vip</li>
            </ul>
            <a href="#">Saiba Mais!</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2022 CSS Flexbox</p>
        <p>Desenvolvido por: I.A.M.</p>
    </footer>
</body>
</html>

style.css

{
	margin: 0;
padding: 0;
	font-family: 'Open Sans'. sans-serif;	
}

Ul{
	list-style: none;
margin: 0;
padding: 0;
}

ul li a{
	text-decoration: none;
}

.flex-container{
	display: flex;
	max-width: 992px;
	margin: auto;
	width: 100px;
}

header{
	background-color: #122A57
	height: 100px;
	display: flex;
	align-itens: center; 
}
