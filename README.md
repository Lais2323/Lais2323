<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Git</title>
    <style>
        .container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            height: 600px;
            width: 650px;
            background-color: #49c6ec;
            margin-left: 150px;
        }

        .texto {
            margin-right: 200px;
            font-size: 18px;
            color: azure;
            width: 550px;
            padding: 18px;
            background-color: #003140;
            font-family: "Montserrat Alternates", sans-serif;
        }

        .imagem {
            background-color: #003140;
        }

        img {
            height: 500px;
            width: 650px;

        }

        h2 {
            font-size: 20px;
            color: #49c6ec;
            font-family: "Montserrat Alternates",sans-serif;
        }

        #button {
            
            border: none;
            width: 66px;
            height: 58px;
            text-decoration: none;
           color: #fff;
            font-family: "Montserrat Alternates", sans-serif;
            background: linear-gradient(to bottom, #D30606, #B50049);
            border-radius: 8px;
            text-shadow: 0px 1px 4px #000000;
            transition: all 1s ease;
            cursor: pointer;
        }

        #button:hover {
            opacity: 0.9;
            background: linear-gradient(to bottom, #CE2286, #D00C3F);
            border-radius: 5px;
            text-shadow: 0px 1px 2px #000000;
            box-shadow: 0px 1px 2px #000000;
        }

        #button img {
            width: 40px;
            height: 40px;
        }
        
        #button2 {
            border: none;
            width: 66px;
            height: 58px;
            text-decoration: none;
           color: #fff;
            font-family: "Montserrat Alternates", sans-serif;
            background: linear-gradient(to bottom, #D30606, #B50049);
            border-radius: 8px;
            text-shadow: 0px 1px 4px #000000;
            transition: all 1s ease;
            cursor: pointer;
        }

        #button2:hover {
            opacity: 0.9;
            background: linear-gradient(to bottom, #CE2286, #D00C3F);
            border-radius: 5px;
            text-shadow: 0px 1px 2px #000000;
            box-shadow: 0px 1px 2px #000000;
        }

        #button2 img {
            width: 42px;
            height: 40px;
            border-radius: 100%;
    
        }

    
    </style>
</head>

<body>

    <div class="container">

        <div class="imagem">
            <img src="code-4.gif" alt="gif">
        </div>
        <div class="texto">
            <p><br>Olá, meu nome é Lais e sou Desenvolvedora Front end e UI Designer. Estou cursando em Análise e
                Desenvolvimento de
                sistemas. <br> Desde que tivo o primeiro contato com front-end percebi que é onde quero focar meus
                estudos, e
                abranger meus conhecimentos, <br>pretendo estudar as tecnologias mais modernas do mercado e evoluir
                sempre !.</p>
            <h2>
                🔥Habilidades</h2>
            <p>HTML5, CSS3, SASS, Javascript ES6 +, SQL, UI / UX nodeJS.</p>
            <h2>
                🚀Pretendo Aprender</h2>
            <p>ReactJS, React Native, SEO e afins.</p>
            <h2>
                📫Quer Falar Comigo?</h2>
            <p>
                Me mande mensagem em alguma dessas redes sociais abaixo!</p>
            <button id="button">Gmail<img id="logo-gmail" src="gmail-preto.png" alt=""></button>

            <button id="button2">Linkedin
                <img id="logo-gmail" src="linedin.png" alt="">
            </button>
        </div>
    </div>
    </div>
    </table>
</body>

</html>
