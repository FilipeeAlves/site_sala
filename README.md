<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            /* * é utilizado para todos os elementos */
            margin: 0;
            /* margem esterna */
            padding: 0;
            /* margem interna */
            box-sizing: border-box;
            /* incluir o preenchimento das bordas */
        }

        body {
            /* elementos flexível em um container */
            display: flex;
            margin: 3px;
            flex-wrap: wrap;
            flex: 1 1 100vw;
        }

        header {
            display: flex;
            margin: 3px;
            background-color: rgb(49, 230, 26);
            flex: 1 1 100vw;
            height: 100px;
        }

        nav {
            display: flex;
            margin: 3px;
            background-color: rgb(49, 230, 26);
            flex: 1 1 200px;
        }

        main {
            display: flex;
            margin: 3px;
            background-color: rgb(49, 230, 26);
            height: calc(100vh - 224px);
            flex: 20 1 500px;
        }

        aside {
            display: flex;
            margin: 3px;
            background-color: rgb(49, 230, 26);
            flex: 1 1 200px;
        }

        footer {
            display: flex;
            margin: 3px;
            background-color: rgb(49, 230, 26);
            height: 100px;
            flex: 1 1 100vw;
        }
    </style>
</head>

<body>
    <header> A Escola Professora Dirce Celestino do Amaral é um espaço acolhedor e inspirador, onde crianças e jovens desenvolvem seu conhecimento e criatividade, guiados por educadores dedicados e apaixonados pela formação e pelo futuro dos alunos. </header>
    <nav> ... </nav>
    <main> <img src="filipe.jpg" alt="">
       <h1>Sou apaixonado por vôlei, sempre buscando aprimorar minhas habilidades na quadra e fortalecer laços com amigos. Além disso, gosto muito de jogos eletrônicos, que me permitem relaxar e me conectar com pessoas de todo o mundo.</h1>
        <h2>A biologia também me fascina, pois me ajuda a entender melhor os seres vivos e os processos da natureza, despertando meu interesse por questões ambientais e de saúde. Estou animado para aprender e crescer em todas essas áreas! </h2>
        </main>
    <aside> Relacionado ao Principal </aside>
    <footer> Rodapé </footer>
</body>

</html>
