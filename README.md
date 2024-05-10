# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Simples</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            animation: fadeIn 1s ease-in-out;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        header {
            background-image: url('https://via.placeholder.com/150');
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            background-size: cover;
            animation: slideInDown 1s ease-in-out;
        }
        @keyframes slideInDown {
            from {
                transform: translateY(-100%);
            }
            to {
                transform: translateY(0);
            }
        }
        header h1 {
            margin: 0;
            padding: 0;
            font-size: 36px;
            font-weight: bold;
        }
        nav {
            background-color: #444;
            padding: 10px 0;
            text-align: center;
            animation: slideInUp 1s ease-in-out;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #555;
        }
        section {
            padding: 20px;
            text-align: justify;
            max-width: 800px;
            margin: auto;
            line-height: 1.6;
            font-size: 16px;
            color: #333;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
            animation: slideInUp 1s ease-in-out;
        }
        @keyframes slideInUp {
            from {
                opacity: 0;
                transform: translateY(50%);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        section h2 {
            color: #333;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
            animation: slideInUp 1s ease-in-out;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1 style="color: #ffd700;">Bem-vindo ao Meu Site Simples</h1>
    </header>
 
    <section>
        <img src="https://neoris.com/documents/20126/241879/iStock-1334575820.jpg/d527ceb3-e256-4856-2ff2-56ec2cee4d2c?t=1654185388133" alt="Imagem Tecnologia">
        <h2 style="color: #333;">Tecnologia: Impacto e Avanços</h2>
        <p>A tecnologia tem sido uma força motriz significativa em nossas vidas, transformando a maneira como vivemos, trabalhamos e nos comunicamos.</p>
        <p>Com o avanço da inteligência artificial, estamos testemunhando sistemas autônomos capazes de aprender e tomar decisões complexas. Isso tem implicações profundas em várias indústrias, desde a medicina até a manufatura.</p>
        <p>Além disso, a Internet das Coisas (IoT) está conectando dispositivos cotidianos à internet, permitindo a automação e a coleta de dados em tempo real. Isso abre caminho para cidades inteligentes, casas inteligentes e uma infinidade de outras aplicações.</p>
        <p>No entanto, também enfrentamos desafios, como questões de privacidade e segurança cibernética. É crucial encontrar um equilíbrio entre inovação e proteção dos direitos individuais.</p>
        <p>À medida que continuamos a avançar, é essencial abordar essas questões de forma responsável, garantindo que a tecnologia beneficie a sociedade como um todo.</p>
    </section>
    <footer>
        <p>&copy; 2024 Meu Site Simples. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
