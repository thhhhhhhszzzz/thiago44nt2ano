<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lugares Turísticos da Europa</title>
    <style>
        body {
            font-family: 'Helvetica', sans-serif;
            background-color: #f7f7f7;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color: #1e3799;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }

        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 20px;
        }

        .destination-card {
            width: 300px;
            margin: 20px;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }

        .destination-card:hover {
            transform: scale(1.05);
        }

        .destination-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .destination-info {
            padding: 15px;
        }

        footer {
            text-align: center;
            background-color: #1e3799;
            color: #fff;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Lugares Turísticos da Europa</h1>
    </header>

    <section>
        <div class="destination-card">
            <img src="paris.jpg" alt="Torre Eiffel, Paris">
            <div class="destination-info">
                <h2>Paris, França</h2>
                <p>Descubra a beleza da Cidade Luz, com seus monumentos icônicos e charme inigualável.</p>
                <a href="paris.html">Saiba mais</a>
            </div>
        </div>

        <div class="destination-card">
            <img src="rome.jpg" alt="Coliseu, Roma">
            <div class="destination-info">
                <h2>Roma, Itália</h2>
                <p>Explore a história e a cultura da capital italiana, com seus monumentos históricos e culinária incrível.</p>
                <a href="rome.html">Saiba mais</a>
            </div>
        </div>

        <div class="destination-card">
            <img src="santorini.jpg" alt="Vista de Santorini, Grécia">
            <div class="destination-info">
                <h2>Santorini, Grécia</h2>
                <p>Relaxe nas deslumbrantes praias e admire as vistas espetaculares dessa ilha grega pitoresca.</p>
                <a href="santorini.html">Saiba mais</a>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Lugares Turísticos da Europa. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
