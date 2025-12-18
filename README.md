
<!DOCTYPE HTML>
<html>
    <head>
        <meta charset="UFT-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title> Chamsiddine Abdullah - CV</title>
        <link rel="stylesheet" href="CV.css">
        <link rel="icon" class="icon" href="./CV.png"> <!-- coube l'icon-->
      <style>
        *{
    
    box-sizing: border-box;
}
.left {
        background: #000;
        color: white;
        padding: 40px 40px;
    }
    .partie-gauche{
        background: #000;
        color: white;
        padding: 40px 40px;
    }
    .name {
        font-size: 2.8rem;
        text-align: center;
        margin: 0;
        line-height: 1.2;
    }
    .profile-img {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        object-fit: cover;
        border: 5px solid white;
        display: block;
        margin: 0 auto 20px;
    }

    h2{
        font-size: 1.8rem;
        margin-bottom: 30px;
        text-transform: uppercase;
        border-bottom: 2px solid #000;
        padding-bottom: 10px;
        display: inline-block;
    }
    h3{
        font-size: 1.3rem;
        text-transform: uppercase;
        border-bottom: 2px solid #fff;
        padding-bottom: 10px;
        margin-bottom: 20px;
        text-align:start;
    }
    .container{
    display: flex;
    gap: 20px; /* espace entre les deux sections */
    align-items: flex-start; 
    padding: 20px;
    }
    .partie-gauche{
        width: 340px;
        background: #000;
        box-shadow: 0 0 20px rgba(0,0,0,0.1);
        color: white;
        display: flex;
        flex-direction: column;
        padding: 10px 100px 10px 10px;
        border-radius: 20px;
        flex-shrink: 0;
    }
    .centrale {
    flex: 1;            /* prend toute la place restante */
    min-width: 0;       /* évite les débordements */
    display: flex;      
}
    .parti_centrale{
        display: flex;
        flex: 1;                       /* prend tout l’espace restant */
        min-width: 0;                 /* évite qu’elle devienne trop étroite */
        background: white;
        padding: 40px;
        border-radius: 20px;
        box-shadow: 0 0 20px rgba(0,0,0,0.1);
        flex-direction: column;
    }
    .contact-info div {
        margin-bottom: 15px;
    }
    .contact-info i {
        margin-right: 10px;
        width: 20px;
    }
    .img_conctact{
        border-radius: 50%;
    }
    .skills, .langues {
        list-style: none;
    }
    .skills li, .langues li {
        margin-bottom: 15px;
        display: flex;
        justify-content: space-between;
    }
    .stars {
        color: #969693;
        justify-content: space-between;
        align-items: center;
    }
    .references {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 30px;
    }
    .ref {
        background: #f9f9f9;
        padding: 20px;
        border-left: 4px solid #000;
    }
        @media (max-width: 768px) {
        .container { grid-template-columns: 1fr; }
        .left { padding: 40px 30px; }
    }
    .argu_centrale{
        font-size: 30px;
        color: rgb(148, 156, 164);
    }
    .caracter{
        color: rgb(137, 152, 167);
    }
    /* Optionnel : petite amélioration mobile */
@media (max-width: 900px) {
    body {
        flex-direction: column;
        padding: 10px;}
    
    .partie-gauche {
        flex: 1 1 auto;
        width: 100%;
        max-width: none;
    }
    
    .centrale {
        padding: 20px;
    }
  }
      </style>
    </head>
    <body>
        <form action="cadre">
            <section class="partie-haute">
                <div class="haute">
                    <div class="left">
                        <img src="photo de profil.jpg" alt="Photo de Chamsiddine" class="profile-img"> 
                        <h1 class="name">CHAMSIDDINE<br>ABDULLAH</h1>
                    </div>
                </div>
            </section>
        <div class="container">
            <section class="partie-gauche">
                <div class="CONTACT">
                    <h3 class="con">contact</h3>
                    <br>    <!--a enlever-->
                    <!--<img class="img_conctact" src="tel.jpeg" alt="tel"> -->
                    <p>📞+336 66 59 35 08</p>
                    <!--<img src="#" alt="mail"> -->
                    <p> ✉️Chamsiddineabdullah@gmail.com</p>
                    <!--<img src="#" alt="loc"> -->
                    <p> 📍14 chemin launay violette 44300 Nantes</p>
                </div>
                <div class="CURSUS">
                    <h3>CURSUS</h3>
                    <p>BUT informatique <br> <strong> IUT Nantes</strong> <br> 2025-2026</p>
                    <p>LYCÉE GÉNÉRALE <br> <strong>lycée de petite-terre  </strong></p>
                </div>
                <div class="PERSONNALITÉ">
                    <h3>Personnalité</h3>
                    <ul class="skills">
                        <li>Curieux et ouvert d'esprit</li>
                        <li>Investi et impliqué</li>
                        <li>Poli et respectueux</li>
                        <li>Esprit d'équipe</li>
                        <li>Compréhensif et à l'écoute</li>
                        <li>Adaptable et flexible</li>
                        <li>Réactif et apprenant rapide</li>
                </div>
                <div class="LANGUE">
                    <h3>Langues</h3>
                    <ul class="langues">
                        <li>Français <span class="stars">★★★★★</span></li>
                        <li>Anglais <span class="stars">★★☆☆☆</span></li>
                        <li>Espagnol <span class="stars">★★☆☆☆</span></li>
                    </ul>
                </div>    
            </section>
            <section class="centrale">
                <div class="parti_centrale">
                    <div class="profil_professionnelle">
                            <h2>Profil Professionnel</h2>
                            <p> Developpeur  en informatique </p>
                    </div>
                    <div class="CURSUS-centrale">
                        <h2>CURSUS</h2>
                        <p>BUT informatique <br> <strong> IUT Nantes</strong> <br> 2025-2028</p>
                        <p>LYCÉE GÉNÉRALE <br> <strong>lycée de petite-terre  </strong></p>
                    </div>
                    <div class="experience_professionnelle">
                        <h2>experience professionnelle</h2>
                        <div class="job">
                            <p class="caracter"> Mai 2025 Conférence au Lycée Polyvalent</p>
                            <!--<h4 class="argu_centrale">Conférence</h4>-->
                            <ul>
                                <li>Maîtrise IA</li>
                                <li>Exploitation IA</li>
                                <li>Pilotage IA</li>
                            </ul>
                        </div>
                        <div class="job">
                            <p class="caracter"><!--Mai 2023 et--> Mai 2024 Nuit du code  au Lycée Polyvalent </p>
                            <!--<h4 class="argu_centrale"> Nuit du code</h4> -->
                            <ul>
                                <li>Projet d'équipe</li>
                                <li>Création et montage de jeu vidéo</li>
                                <li>Présentation du projet</li>
                            </ul>
                        </div>
                        <div class="job">
                            <p class="caracter"><!--Mai 2024 et--> Mai 2023 Nuit du code  au Lycée Polyvalent </p>
                            <!--<h4 class="argu_centrale"> Nuit du code</h4> -->
                            <ul>
                                <li>Projet d'équipe</li>
                                <li>Création et montage de jeu vidéo</li>
                                <li>Présentation du projet</li>
                            </ul>
                        </div>
                    </div>
                    <div class="referent">
                        <h2>Références</h2>
                        <div class="references">
                            <div class="ref">
                                <h4>Pascal LECOCQ</h4>
                                <p>Proviseur du lycée de Petite Terre</p>
                                <p>Tél : 02 69 60 55 66</p>
                                <p>hello@reallygreatsite.com</p>
                            </div>
                            <div class="ref">
                                <h4>Christophe MILLET</h4>
                                <p>Directeur de l'IUT de Nantes</p>
                                <p>Tél : 02 40 30 60 02</p>
                                <p>Christophe.Millet@univ-nantes.fr</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        </form>
    </body>
</html>
