<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ihr Handyladen für Smartphones, Zubehör und Reparaturen.">
    <title>HandyShop - Ihr Shop für Smartphones und Zubehör</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <h1>HandyShop</h1>
            </div>
            <ul class="nav-links">
                <li><a href="#home">Startseite</a></li>
                <li><a href="#produkte">Produkte</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#kontakt">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-text">
            <h2>Willkommen bei HandyShop</h2>
            <p>Ihr zuverlässiger Partner für Smartphones, Zubehör und Reparaturen.</p>
        </div>
    </section>

    <section id="produkte" class="products">
        <h2>Unsere Produkte</h2>
        <div class="product-list">
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Smartphone 1">
                <h3>Smartphone Modell A</h3>
                <p>Perfektes Smartphone für jeden Bedarf.</p>
                <span>€699,00</span>
                <button>Kaufen</button>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Smartphone 2">
                <h3>Smartphone Modell B</h3>
                <p>Leistungsstark und elegant.</p>
                <span>€799,00</span>
                <button>Kaufen</button>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/300" alt="Smartphone 3">
                <h3>Smartphone Modell C</h3>
                <p>Innovativ und effizient.</p>
                <span>€899,00</span>
                <button>Kaufen</button>
            </div>
        </div>
    </section>

    <section id="services" class="services">
        <h2>Unsere Services</h2>
        <div class="service-list">
            <div class="service-item">
                <h3>Reparaturservice</h3>
                <p>Wir reparieren Ihr Smartphone schnell und zuverlässig.</p>
            </div>
            <div class="service-item">
                <h3>Zubehör</h3>
                <p>Hüllen, Ladegeräte und mehr – alles für Ihr Smartphone.</p>
            </div>
            <div class="service-item">
                <h3>Beratung</h3>
                <p>Wir helfen Ihnen, das perfekte Smartphone zu finden.</p>
            </div>
        </div>
    </section>

    <section id="kontakt" class="contact">
        <h2>Kontakt</h2>
        <p>Haben Sie Fragen? Kontaktieren Sie uns!</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">E-Mail:</label>
            <input type="email" id="email" name="email" required>
            <label for="nachricht">Nachricht:</label>
            <textarea id="nachricht" name="nachricht" required></textarea>
            <button type="submit">Absenden</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 HandyShop. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
