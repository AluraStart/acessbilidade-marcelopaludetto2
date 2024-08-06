[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15510924&assignment_repo_type=AssignmentRepo)
Aula 01
Trabalhando no header

Alinhando conteúdo à direita
https://getbootstrap.com/docs/4.3/utilities/flex/#justify-content

Mudar fonte
tipo da fonte e cor

Mudar cor do background menu

Adicionar imagem à esquerda

Aumentar espaçamento



div*3

modal
Galeria:  src="img/projeto-1.png"
    class="img-fluid w-100"

    footer
    bootstrap icons <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">

    --------------------------

    <title>Foco Visível</title>
    <style>
        a {
            color: blue;
            text-decoration: none;
        }
        a:focus {
            outline: 2px solid orange;
            background-color: lightyellow;
        }
    </style>
</head>
<body>
    <a href="#">Link acessível</a>
</body>
</html>
Dicas de Acessibilidade:
Visibilidade do Foco: Garanta que o estado de foco seja visível e distinto. Evite remover o outline padrão sem substituí-lo por um estilo visível.
Consistência: Certifique-se de que todos os elementos interativos (links, botões, campos de formulário) tenham estados de foco bem definidos.