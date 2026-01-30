<!doctype html>
<html lang="fr">
    <head>
        <meta charset="UTF-8" />
        <title>Portfolio – ETOKE Ambroise</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <header>
            <h1>ETOKE Bagnonkm Ambroise</h1>
            <p>Développeur Web Junior • HTML & CSS • Trading</p>
            <nav>
                <a href="#apropos">À propos</a>
                <a href="#competence">Compétence</a>
                <a href="#projet">Projet</a>
                <a href="#contact">Contact</a>
            </nav>
        </header>

        <main>
            <!--section a propos de moi-->
            <section id="apropos">
                <h2>À propos de moi:</h2>
                <p>
                    Passionné par l’informatique, je me suis lancé dans le développement web afin de créer des sites
                    simples et modernes. Je suis développeur web junior avec une bonne maîtrise du HTML et du CSS. En
                    parallèle, je découvre le trading et j’approfondis progressivement mes connaissances dans ce
                    domaine.
                </p>
            </section>
            <!--Competence-->
            <section id="competence">
                <h2>Mes compétences:</h2>
                <ul>
                    <li>Maitrise du HTML</li>
                    <li>Bonne base en CSS</li>
                    <li>Trader indépendant</li>
                </ul>
            </section>
            <!--projet-->
            <section id="projet">
                <h2>Mes projects:</h2>
                <ul>
                    <li>Portfolio personnel</li>
                    <li>Page de formulaire HTML</li>
                    <li>Page produit e-commerce</li>
                </ul>

            </section>
            <!--contact-->
            <section id="contact">
                <h2>Contact:</h2>
                <p>
                    Numéro WhatsApp:
                    <a href="tel:+22879474327">+228 79 47 43 27</a>
                </p>
                <p>
                    Email:
                    <a href="mailto:etokeambroise96@gmail.com">etokeambroise96@gmail.com</a>
                </p>
            </section>
        </main>
        <footer>
            <p>© 2026 ETOKE Bagnonkm Ambroise | Tous droits réservés.</p>
        </footer>




        * RESET PROPRE */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* BODY */
body {
    font-family: Arial, sans-serif;
    background-color:#080414;
    color: hsl(0, 100%, 97%);
    text-align: center;
    line-height: 1.6;
}

/* HEADER */
header {
    background-color: rgba(17, 34, 51, 0.9);
    font-family: Arial, Helvetica, sans-serif;
    padding: 20px;
    border-radius: 15px;
    max-width: 1000px;
    margin: 20px auto;
    box-shadow: 0 8px 25px rgba(0,0,0,0.35);
}

/* NAVIGATION */
nav {
    margin-top: 12px;
}

nav a {
    text-decoration: none;
    color: #ffffff;
    margin: 12px;
    font-weight: bold;
    transition: color 0.3s ease;
   
}

nav a:hover {
    color: #cbd5e0;
}

/* TITRES */
h2 {
    padding: 2px;
    margin: 2px 0;
}

/* SECTIONS */
section {
    padding: 20px;
    max-width: 900px;
    margin: 20px auto;
    background-color: #3f3c3c;
    box-shadow: 0 8px 25px rgba(0,0,0,0.35);
}

/* PARAGRAPHES */
p {
    margin: 15px 0;
}

/* LISTES */
ul {
    list-style: none;
    padding: 0;
}

ul li {
    background:#925858;
    padding: 10px;
    margin: 10px auto;
    text-align: center;
    border-left: 6px solid blue;
    max-width: 600px;
     border-radius: 10px;
}

/* LIENS CONTACT SEULEMENT */
#contact a {
    text-decoration: none;
    color: #ffffff;
    font-weight: bold;
    
}
.apropos, .competence, .projet, .contact {
    text-align: center;
}


/* FOOTER */
footer {
    background: rgba(17, 34, 51, 0.9);
    text-align: center;
    padding: 15px;
    margin-top: 30px;
    text-align: center;

} 
    </body>
</html>
