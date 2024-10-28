<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CHI SIAMO?</title>
    <link rel="stylesheet" href="ChiStyles.css">
</head>
<body>

 <header>
        <div class="logo">
            <img src="Logo.png" alt="Logo" width="50" height="50">
        </div>
        <nav>
            <ul>
                <li><a href="Pagina iniziale.html" class="menu-link">Home</a></li>
</header>
<section>
    <h2>Un gruppo di ragazzi</h2>
    <p>Siamo un gruppo di ragazzi che hanno fatto questo sito per un compito di infomartica, siamo stati in tre a creare questo progetto meraviglioso, due di noi hanno fatto le pagine mentre l'altro si è occupato a cercare infomazioni rigurdanante la vita di Van Gogh, i quadri e le loro storie.</p>
 <br>


</br>
<h2>Come abbiamo creato il sito?</h2>
<p>Per creare questo sito abbiamo preso spunto ad altri siti web, uno di noi ha creato un prototipo prima di impaginare la pagina, abbiamo anche chiesto all'IA di correggere alcuni codici, ovviamente il resto l'abbiamo creato noi. Gli immagini e i background sono presi dal web e il logo usato è quello della nostra scuola. </p>
</section>

<div class="footer">
    Grazie per aver dato un'occhiata al nostro sito!
</div>

</body>
</html>
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Van Gogh | Scopri di più</title>
    <link rel="stylesheet" href="PaginaStyle.css">
</head>
<body>

    <header>
        <div class="logo">
            <img src="Logo.png" alt="Logo" width="50" height="50">
        </div>
        <nav>
            <ul>
                <li><a href="Chi siamo.html">Chi Siamo</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero-section" style="background-image: url(NotteStellata.jpeg); background-size: cover; padding: 50px; text-align: center;">
        <div>
            <h1>VAN GOGH</h1>
            <button><a href="Vita di Van Gogh.html" style="color: inherit; text-decoration: none;">Scopri di più</a></button>
        </div>
    </section>

    <section class="gallery-section">
    <h2>QUADRI PIÙ FAMOSI</h2>
    <div class="gallery">
        <div>
            <a href="NotteStellata.html"> 
                <img src="QuadroStelle.jpeg" alt="La Notte Stellata">
            </a>
        </div>
        <div>
            <a href="Girasoli.html"> 
                <img src="QuadroGirasoli.jpeg" alt="I Girasoli">
            </a>
        </div> 
        <div>
            <a href="Autoritratto.html"> 
                <img src="QuadroVan.jpeg" alt="Autoritratto di Van Gogh">
            </a>
        </div> 
    </div>
</section>
    <!-- Footer -->
    <footer>
        <div>
            <h3>Informazioni</h3>
            <p>Sito informativo sui quadri di Van Gogh</p>
        </div>
        <div>
            <h3>Contatti</h3>
            <p>Email: info@vangogh.com</p>
        </div>
        <div>
            <h3>Orario</h3>
            <p>Lun - Ven: 08:00 - 14:00</p>
            <p>Orari scolastici del Freud</p>
        </div>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f2f2f2;
    color: #333;
    background-image: url('NotteStellata.jpeg');
    background-repeat: no-repeat;
    background-size: cover;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
}

header {
    color: #333;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 20px;
    background-color: #333;
}

header a {
    color: #fff;
    text-decoration: none;
}

section {
    max-width: 800px;
    margin: 2em auto;
 padding: 5em;
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #4a90e2;
}

.image {
    text-align: center;
}

.image img {
    max-width: 100%;
    height: auto;
}

.footer {
    margin-top: auto;
    text-align: center;
    padding: 1em;
    background-color: #333;
    color: #fff;
}
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Van Gogh | Scopri di più</title>
    <link rel="stylesheet" href="StylesStelle.css"> <!-- Link al file CSS -->
</head>
<body>

    <!-- Header -->
    <header>
        <div class="logo">
            <img src="Logo.png" alt="Logo" width="50" height="50">
        </div>
        <nav>
            <ul>
                <li><a href="Pagina iniziale.html" class="menu-link">Home</a></li>
                <li><a href="Chi siamo.html" class="menu-link">Chi Siamo</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero-section">
        <h1>LA NOTTE STELLATA</h1>
    </section>

    <!-- Descrizione del Quadro con Immagine -->
    <section class="gallery-section">
        <div class="text">
            <h2>Uno dei dipinti più apprezzati</h2>
            <p>"La Notte Stellata" è uno dei dipinti più iconici e riconoscibili di Vincent van Gogh, realizzato nel giugno del 1889 durante il suo soggiorno presso l'ospedale psichiatrico di Saint-Rémy-de-Provence, in Francia. Questo capolavoro rappresenta una sintesi perfetta tra l'arte e le emozioni umane, trasformando la bellezza del cielo notturno in un'esperienza visiva che trascende il semplice atto di osservare.</p>
            
            <p>In un periodo di grande tumulto personale e di crisi mentale, Van Gogh trovò conforto e ispirazione nella natura circostante e nel cielo che lo sovrastava. Nonostante le sue lotte con la malattia e la solitudine, il pittore catturò il mondo che lo circondava in modo profondo e personale, rendendo "La Notte Stellata" non solo un'opera d'arte, ma anche un riflesso della sua anima.</p>
        </div>
        <div class="image">
            <img src="QuadroStelle.jpeg" alt="La Notte Stellata di Vincent van Gogh">
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>Sito informativo sui quadri di Van Gogh</p>
        <p>Email: info@vangogh.com</p>
        <p>Lun - Ven: 08:00 - 14:00</p>
    </footer>

</body>
</html>
!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Van Gogh | Autoritratto</title>
    <link rel="stylesheet" href="StylesVan.css">
</head>
<body>

     <!-- Header -->
    <header>
        <div class="logo">
            <img src="Logo.png" alt="Logo" width="50" height="50">
        </div>
        <nav>
            <ul>
                <li><a href="Pagina iniziale.html" class="menu-link">Home</a></li>
                <li><a href="Chi siamo.html" class="menu-link">Chi Siamo</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero-section" style="background-image: url('NotteStellata.jpeg'); background-size: cover; background-position: center;">
        <h1>AUTORITRATTO</h1>
    </section>

    <!-- Descrizione del Quadro con Immagine -->
    <section class="gallery-section">
        <div class="text">
            <h2>Un’immagine dell’anima dell’artista</h2>
            <p>L'"Autoritratto" di Vincent van Gogh, dipinto nel 1889, è uno dei suoi lavori più personali e intensi. Il dipinto mostra un volto segnato dalle difficoltà e dalla sofferenza, ma anche dalla determinazione. Questo autoritratto rappresenta la lotta interiore di Van Gogh e il suo desiderio di esprimere la propria identità attraverso l'arte.</p>
            
            <p>L'opera è caratterizzata da colori vivaci e pennellate energiche, che riflettono il suo stile unico e il suo stato emotivo. L'autoritratto non è solo un'immagine del suo aspetto fisico, ma anche un riflesso della sua anima tormentata e creativa.</p>
        </div>
        <div class="image">
            <img src="QuadroVan.jpeg" alt="Autoritratto di Vincent van Gogh">
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>Sito informativo sui quadri di Van Gogh</p>
        <p>Email: info@vangogh.com</p>
        <p>Lun - Ven: 08:00 - 14:00</p>
    </footer>

</body>
</html>
