# html-css
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Repostório Público - Andrey Gdula</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Space+Mono&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');

        :root {
            --font-title: 'Press Start 2P', 'Bebas Neue', 'Arial', 'sans-serif';
            --font-text: 'Space Mono', 'Arial', 'sans-serif';
            --font-project: 'Arial', 'Helvetica', 'sans-serfi';
            --color01: #0B2447;
            --color02: #FAFAFA;
            --color03: #0B242C;
            --color04: #2A6478;
        }
        body {
            background-color: var(--color01);
            color: var(--color02);
        }
        h1 {
            font-family: var(--font-title);
            font-size: 1.2em;
            font-weight: normal;
            text-align: left;
            padding: 20px;
            margin-top: 0px;
        }
        h2 {
            font-family: var(--font-title);
            font-size: 1em;
            font-weight: normal;
            text-align: left;
            padding: 20px;
            padding-bottom: 10px;
        }
        p {
            font-family: var(--font-text);
            font-size: 1em;
            font-weight: normal;
            text-align: left;
            line-height: 2em;
            padding: 10px;
            text-indent: 30px;
        }
        div.project {
            background-color: var(--color04);
            border-radius: 20px;
            width: 50%;
            padding: 5px 10px 10px 10px;
        }
        ul {
            list-style-type: '\2714\00A0\00A0';
        }
        a.project {
            display: block;
            color: var(--color02);
            font-family: var(--font-project);
            text-decoration: none;
            font-size: 1.2em;
            font-weight: bold;
            padding: 10px 10px 10px 10px;
        }
        a.project:hover {
            background-image: linear-gradient(to right, var(--color02), transparent);
            color: var(--color03);
            transition-duration: .5s;
            border-radius: 10px;
            width: 40%;
        }
    </style>
</head>
<body>
    <h1>
        Repositório Público do Andrey Gdula
    </h1>
    <p>
        Aqui estão os meus projetos.
    </p>
    <div class="project">
        <h2>Meus projetos em HTML5 e CSS3:</h2>
        <ul>
            <li><a href="http://andreygdula.github.io/projeto-android" target="_blank" class="project">Projeto Android</a></li>
            <li><a href="https://andreygdula.github.io/projeto-cordel" target="_blank" class="project">Projeto Cordel</a></li>
            <li><a href="https://andreygdula.github.io/html-css/Exercícios%20-%20HTML/projetos/social/social.html" target="_blank" class="project">Redes Sociais</a></li>
        </ul>
    </div>
</body>
</html>