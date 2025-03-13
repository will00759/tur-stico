<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lugares Turísticos na Europa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px;
        }
        .card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 250px;
            margin: 15px;
            overflow: hidden;
            transition: transform 0.3s ease-in-out;
        }
        .card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }
        .card h3 {
            font-size: 1.5em;
            margin: 10px;
        }
        .card p {
            font-size: 1em;
            color: #555;
            margin: 0 10px 10px;
        }
        .card:hover {
            transform: translateY(-10px);
        }
    </style>
</head>
<body>
    <header>
        <h1>Descubra os Melhores Lugares Turísticos na Europa</h1>
        <p>Explore os destinos mais fascinantes da Europa, com história, cultura e belezas naturais!</p>
    </header>

    <section>
        <div class="card">
            <img src="https://example.com/eiffel-tower.jpg" alt="Torre Eiffel, Paris">
            <h3>Torre Eiffel, Paris</h3>
            <p>A Torre Eiffel é um dos monumentos mais emblemáticos do mundo, localizada em Paris, França. Com 330 metros de altura, oferece uma vista incrível da cidade.</p>
        </div>

        <div class="card">
            <img src="https://example.com/colosseum.jpg" alt="Coliseu, Roma">
            <h3>Coliseu, Roma</h3>
            <p>O Coliseu é uma das maravilhas da Roma Antiga. Este enorme anfiteatro foi palco de combates entre gladiadores e outras apresentações espetaculares.</p>
        </div>

        <div class="card">
            <img src="https://example.com/azores.jpg" alt="Açores, Portugal">
            <h3>Açores, Portugal</h3>
            <p>Os Açores são um arquipélago no meio do Atlântico, conhecidos pela sua beleza natural impressionante, com lagos vulcânicos, montanhas e águas termais.</p>
        </div>

        <div class="card">
            <img src="https://example.com/parthenon.jpg" alt="Partenon, Atenas">
            <h3>Partenon, Atenas</h3>
            <p>O Partenon é um templo dedicado à deusa Atena, localizado na Acrópole de Atenas, Grécia. Ele é um símbolo de resistência e beleza da civilização grega antiga.</p>
        </div>

        <div class="card">
            <img src="https://example.com/sagrada-familia.jpg" alt="Sagrada Família, Barcelona">
            <h3>Sagrada Família, Barcelona</h3>
            <p>Desenhada por Antoni Gaudí, a Sagrada Família é uma das igrejas mais famosas do mundo, com sua arquitetura única e detalhada, localizada em Barcelona, Espanha.</p>
        </div>

        <div class="card">
            <img src="https://example.com/blue-danube.jpg" alt="Rio Danúbio, Viena">
            <h3>Rio Danúbio, Viena</h3>
            <p>O Rio Danúbio atravessa várias cidades europeias, e em Viena, oferece um cenário deslumbrante para passeios de barco, com a cidade histórica ao fundo.</p>
        </div>
    </section>

</body>
</html>
