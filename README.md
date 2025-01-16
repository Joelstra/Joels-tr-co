<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Snickarföretag som erbjuder takarbeten, fasadarbeten, markarbeten, köksrenoveringar och utbyggnader. Se våra tidigare projekt och kontakta oss för offert!">
    <title>Snickarföretag - Din Partner för Bygg och Renovering</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            position: relative;
            background: url('/mnt/data/joels trä loga utan bakgrund(1).svg') no-repeat center/contain, #333;
            color: #fff;
            text-align: center;
            padding: 4rem 1rem;
        }
        header h1 {
            font-size: 2.5rem;
            margin: 0;
        }
        header p {
            margin: 1rem 0;
            font-size: 1.2rem;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 1rem 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
            font-size: 1.1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 5rem 1rem;
            position: relative;
        }
        .hero button {
            background: #ff4500;
            color: #fff;
            border: none;
            padding: 0.8rem 1.5rem;
            font-size: 1rem;
            cursor: pointer;
            margin-top: 1rem;
        }
        .hero button:hover {
            background: #e63900;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .services, .portfolio {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }
        .service, .project {
            background: #fff;
            border: 1px solid #ddd;
            padding: 1rem;
            flex: 1 1 calc(33.333% - 2rem);
            box-sizing: border-box;
            text-align: center;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 2rem 1rem;
            margin-top: 2rem;
        }
        @media (max-width: 768px) {
            .service, .project {
                flex: 1 1 calc(50% - 2rem);
            }
        }
        @media (max-width: 480px) {
            .service, .project {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Välkommen till Joel's Trä och Co</h1>
        <p>Din partner för tak, fasader, markarbete och mer.</p>
    </header>
    <nav>
        <a href="#tjanster">Tjänster</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#kontakt">Kontakt</a>
    </nav>
    <div class="hero">
        <h2>Professionella bygg- och renoveringstjänster</h2>
        <p>Vi levererar kvalitet för varje projekt - stort som smått.</p>
        <button onclick="location.href='#kontakt'">Kontakta oss idag</button>
    </div>
    <div class="container">
        <section id="tjanster">
            <h2>Våra Tjänster</h2>
            <div class="services">
                <div class="service">
                    <h3>Takbyte</h3>
                    <p>Professionella och effektiva takbyten för alla typer av fastigheter.</p>
                </div>
                <div class="service">
                    <h3>Fasadarbeten</h3>
                    <p>Vi förbättrar och skyddar din fasad med hållbara lösningar.</p>
                </div>
                <div class="service">
                    <h3>Markarbeten</h3>
                    <p>Specialister på dränering och andra markarbeten.</p>
                </div>
                <div class="service">
                    <h3>Köksrenovering</h3>
                    <p>Design och installation av moderna och funktionella kök.</p>
                </div>
                <div class="service">
                    <h3>Utbyggnad</h3>
                    <p>Vi hjälper dig att skapa mer utrymme med smarta utbyggnadslösningar.</p>
                </div>
            </div>
        </section>
        <section id="portfolio">
            <h2>Portfolio</h2>
            <div class="portfolio">
                <div class="project">
                    <h3>Renovering av ladugård</h3>
                    <p>En komplett renovering av en gammal ladugård med fokus på hållbarhet.</p>
                </div>
                <div class="project">
                    <h3>Takbyte på villa</h3>
                    <p>Ett effektivt takbyte som återställde både funktion och estetik.</p>
                </div>
                <div class="project">
                    <h3>Ny altan</h3>
                    <p>Byggnation av en rymlig och modern altan.</p>
                </div>
            </div>
        </section>
        <section id="kontakt">
            <h2>Kontakt</h2>
            <p>Kontakta oss för en kostnadsfri offert eller om du har några frågor!</p>
            <p>Email: info@snickarföretag.se</p>
            <p>Telefon: 070-123 45 67</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 Joel's Trä och Co. Alla rättigheter förbehållna.</p>
    </footer>
</body>
</html>
