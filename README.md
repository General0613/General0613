

<!---
General0613/General0613 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>İnşaat Şirketi</title>
</head>
<body>

    <header>
        <h1>İnşaat Şirketi</h1>
        <nav>
            <ul>
                <li><a href="#home">Ana Sayfa</a></li>
                <li><a href="#about">Hakkımızda</a></li>
                <li><a href="#services">Hizmetler</a></li>
                <li><a href="#projects">Projeler</a></li>
                <li><a href="#contact">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Hoş Geldiniz</h2>
        <p>İnşaat ihtiyaçlarınız için buradayız.</p>
    </section>

    <section id="about">
        <h2>Hakkımızda</h2>
        <p>İnşaat sektöründe uzun yıllardır hizmet vermekteyiz. Yüksek kaliteli işçilik ve müşteri memnuniyeti önceliğimizdir.</p>
    </section>

    <section id="services">
        <h2>Hizmetlerimiz</h2>
        <ul>
            <li>Yeni İnşaat</li>
            <li>Tadilat ve Restorasyon</li>
            <li>Proje Yönetimi</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projelerimiz</h2>
        <p>Referanslarımızı inceleyin.</p>
    </section>

    <section id="contact">
        <h2>İletişim</h2>
        <p>Bize ulaşın: info@insaatsirketi.com</p>
    </section>

    <footer>
        <p>&copy; 2023 İnşaat Şirketi. Tüm hakları saklıdır.</p>
    </footer>

</body>
</html>


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav li {
    display: inline;
    margin-right: 20px;
}

nav a {
    text-decoration: none;
    color: #fff;
}

section {
    padding: 40px 20px;
    text-align: center;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    position: absolute;
    width: 100%;
    bottom: 0;
}
