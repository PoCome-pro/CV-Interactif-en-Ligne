<!DOCTYPE html>
<html lang="fr"> <!-- Indique que le document est en HTML5 et que la langue est le francais -->
<head>
    <meta charset="UTF-8"> <!-- Definit l'encodage des caracteres en UTF-8 pour supporter les caracteres speciaux -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Rend la page responsive en ajustant l'echelle pour les appareils mobiles -->
    <title>CV de C&ocirc;me Lux</title> <!-- Definit le titre de la page affiche dans l'onglet du navigateur -->	
    <link href="https://fonts.googleapis.com/css2?family=Frank Ruhl Libre:wght@700&family=Rockwell&display=swap" rel="stylesheet">	
    <!-- Lien vers une police Google Fonts pour personnaliser l'apparence du texte -->

    <style> 
/* Definition des styles CSS directement dans la page */
body {
    font-family: 'Rockwell', serif; /* Police principale du texte */
    margin: 0; /* Retire les marges par defaut */
    background-color: #f5f5f5; /* Couleur de fond gris clair */
}

.header {
    background-color: #d62839; /* Couleur de fond rouge pour l'en-tete */
    color: black; /* Texte en noir */
    padding: 20px; /* Espacement interne de 20px */
    text-align: center; /* Centre le texte */
}

nav {
	background-color: #FFFFFF;
	padding: 10px;
	text-align: center;
}

nav a{
	color: black;
	padding: 10px 20px;
	text-decoration: none;
	margin: 0 15px;
	border-radius: 5px;
}

nav a:hover{
	background-color: #d62839;
}


.header-content {
    display: flex; /* Utilise un conteneur flex pour aligner le contenu */
    justify-content: center; /* Centre horizontalement les elements */
    align-items: center; /* Centre verticalement les elements */
}

.profile-photo {
    width: 100px; /* Largeur fixe de l'image */
    height: auto; /* Ajuste la hauteur proportionnellement */
    margin-right: 20px; /* Ajoute un espace entre l'image et le texte */
    border-radius: 50%; /* Rondeur des bords pour une image circulaire */
}

.name {
    font-size: 36px; /* Taille du texte pour le nom */
    margin: 0; /* Aucune marge externe */
    font-family: 'Franklin Gothic Demi', sans-serif; /* Police specifique pour les titres */
}

.subheading {
    font-size: 14px; /* Taille reduite pour le sous-titre */
    margin: 5px 0; /* Marge verticale de 5px */
}

.info {
    font-size: 12px; /* Taille encore plus reduite pour les informations */
    margin: 5px 0; /* Marge verticale de 5px */
}

.container {
    display: flex; /* Organisation en colonnes */
    margin: 20px; /* Marges autour du conteneur */
}

.left-column {
    flex: 1; /* Prend un espace egal a la moitie du conteneur */
    margin-right: 20px; /* Espace a droite */
    background: #ffffff; /* Fond blanc */
    padding: 20px; /* Espacement interne */
    border-radius: 5px; /* Coins legerement arrondis */
    box-shadow: 0 2px 5px rgba(0,0,0,0.1); /* Ombre subtile */
}

.right-column {
    flex: 1; /* Même espace que la colonne de gauche */
    background: #ffffff; /* Fond blanc */
    padding: 20px; /* Espacement interne */
    border-radius: 5px; /* Coins legerement arrondis */
    box-shadow: 0 2px 5px rgba(0,0,0,0.1); /* Ombre subtile */
}

.left-column, .right-column {
    text-align: left; /* Aligner le texte a gauche */
}


h2 {
    font-size: 18px; /* Taille du texte des titres de section */
    color: black; /* Couleur du texte noir */
    border-bottom: 10px solid #d62839; /* Ligne rouge epaisse sous le titre */
    padding-bottom: 5px; /* Espacement interne vers le bas */
    margin-bottom: 10px; /* Espace en dessous du titre */
    font-family: 'Franklin Gothic Demi', sans-serif; /* Police specifique pour les titres */
	text-align: left; /* Aligner les titres a gauche */
}

p {
    font-size: 14px; /* Taille du texte des paragraphes */
    line-height: 1.5; /* Espacement entre les lignes */
    color: black; /* Texte en noir */
}

.title-date {
    font-weight: bold; /* Met en gras les titres et dates */
}

.footer {
    background-color: #d62839; /* Fond rouge pour le pied de page */
    color: black; /* Texte en noir */
    text-align: center; /* Texte centre */
    padding: 10px; /* Espacement interne */
    position: relative; /* Position normale */
}

.footer p {
    margin: 5px 0; /* Marges reduites pour les paragraphes du pied de page */
}

ul {
    list-style-type: none; /* Retire les puces des listes */
    padding: 0; /* Retire le retrait interne */
}

li {
    margin-bottom: 10px; /* Espacement entre les elements de liste */
    padding: 5px; /* Espacement interne */
    border-bottom: 1px solid #eee; /* Ligne separatrice entre les elements */
}

    </style>
</head>


<body>
    <header class="header"> <!-- En-tete principale -->
        <div class="header-content"> <!-- Conteneur pour l'image et le texte -->
            <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAMCAgMCAgMDAwMEAwMEBQgFBQQEBQoHBwYIDAoMDAsKC..." alt="Photo de Profil de C&ocirc;me Lux" class="profile-photo">
            <div class="header-text">
                <h1 class="name">LUX C&ocirc;me</h1> <!-- Nom principal -->
                <p class="subheading">&Eacute;TUDIANT EN <abbr title="	Bachelor universitaire de technologie	"> 	BUT	</abbr> R&Eacute;SEAUX ET T&Eacute;L&Eacute;COMMUNICATIONS</p> <!-- Sous-titre -->
                <p class="info">18 ANS | NANCY</p> <!-- Informations de base -->
            </div>
        </div>
    </header>
	<nav>
		<a href="#objectif">OBJECTIF</a>			
		<a href="#competence">COMPETENCES</a>				
		<a href="#experience">EXPERIENCE</a>				
		<a href="#formation">FORMATION</a>			
		<a href="#benevolat">B&Eacute;N&Eacute;VOLAT</a>				
    <div class="container"> <!-- Conteneur pour les deux colonnes -->
        <div class="left-column"> <!-- Colonne gauche -->
            <section class="objective"	id="objectif"> <!-- Section objectif -->
                <h2>OBJECTIF</h2> <!-- Titre 2-->
                <p>
                    Curieux et rigoureux, j&#39;appr&eacute;cie <br/>    
                    autant le travail en autonomie que la <br/>
                    collaboration en &eacute;quipe, que ce soit <br/>
                    pour mener &agrave; bien des projets ou <br/>
                    pour approfondir mes connaissances <br/>
                    en informatique.
                </p>
                <p>
                    Mon objectif est d&#39;obtenir <br/>
                    ce poste afin de mettre en pratique mon savoir <br/>
                    et mon exp&eacute;rience tout en surmontant <br/>
                    les obstacles au sein de votre entreprise. <br/> <br/> <br/>
                </p>
            </section>
            <section class="competences" id="competence"> <!-- Section competences -->
                <h2>COMP&#201;TENCES</h2> <!-- Titre 2-->
                <p><strong>Langues :</strong> <!-- Texte en gras --> <br/>Fran&ccedil;ais (Langue Natale),<br/> Anglais (B2),<br/> Allemand (A2)</p>
                <p><strong>Logiciels :</strong> <!-- Texte en gras --> <br/>Cisco Packet Tracer, <br/>Arduino <abbr title="	Environnement de D&eacute;veloppement	"> 	IDE	</abbr>, <br/>GanttProjet, <br/>SolidWorks</p>
                <p><strong>Certifications :</strong> <!-- Texte en gras --> <br/>PIX (349 Points), <br/>Projet Voltaire (En cours)</p>
                <p><strong>Professionnelles :</strong> <!-- Texte en gras --> <br/>Gestion de projets, <br/>Programmation (C, C++, Python, 
				<abbr title="	Matrix Laboratory	"> 	MATLAB	</abbr>, 
				<abbr title="	HyperText Markup Language	"> 	HTML	</abbr>, 
				<abbr title="	Cascading Style Sheets 	"> 	CSS	</abbr>), 
				<br/>Leadership, <br/>R&eacute;solution de Probl&egrave;mes</p>
            </section>
        </div>
        <div class="right-column"> <!-- Colonne droite -->
            <section class="experience"  id="experience"> <!-- Section experience -->
                <h2>EXP&#201;RIENCE</h2> <!-- Titre 2-->
                <ul>
                    <li>
                        <strong>OUVRIER AGRICOLE</strong> <!-- Texte en gras -->- <abbr title="	Exploitation Agricole &agrave; Responsabilit&eacute; Limit&eacute;e	"> 	EARL	</abbr> LES TRENTES D&#39;ARPENTS (&Eacute;t&eacute; 2019&ndash;2023)
                        <p><abbr title="	Contrat de travail &agrave; Dur&eacute;e D&eacute;termin&eacute;e	"> 	CDD	</abbr> de 2 mois chaque &eacute;t&eacute;. Moisson et gestion des r&eacute;coltes.</p>
                    </li>
                    <li>
                        <strong>STAGE D&#39;OBSERVATION EN CABINET D&#39;AVOCAT</strong> <!-- Texte en gras -->- 
						<abbr title="	Soci&eacute;t&eacute; d'Exercice Lib&eacute;ral &agrave; Responsabilit&eacute; Limit&eacute;e	"> 	SELARL	</abbr> 
						<abbr title="	Nom du Cabinet d'Avocats	"> 	MCMB	</abbr> (Juin 2022)
                        <p>Stage de d&eacute;couverte en droit, observation du r&ocirc;le d&#39;un avocat pour les clients.</p>
                    </li>
                    <li>
                        <strong>STAGE D&#39;OBSERVATION EN ENTREPRISE PHARMACEUTIQUE</strong> <!-- Texte en gras -->- <abbr title="	Allergologisk Laboratorium K&oslash;benhavn	"> 	ALK	</abbr> France (F&eacute;vrier 2021)
                        <p>Observation des fonctions d&#39;une entreprise et de l&#39;importance de ses flux internes et externes.</p>
                    </li>
                </ul>
            </section>
            <section class="formation" id="formation"> <!-- Section formation -->
                <h2>FORMATION</h2> <!-- Titre 2-->
                <ul>
                    <li>
                        <strong>BACHELOR UNIVERSITAIRE DE TECHNOLOGIE</strong> <!-- Texte en gras -->- <abbr title="	Institut Universitaire de Technologie	"> 	IUT	</abbr> NANCY-BRABOIS (2024-2027)
                        <p><abbr title="	Bachelor Universitaire de Technologie	"> 	BUT	</abbr> R&eacute;seaux et T&eacute;l&eacute;communications, actuellement en 1&#39;re ann&eacute;e d&#39;&eacute;tude.</p>
                    </li>
                    <li>
                        <strong>BACCALAUR&#201;AT TECHNOLOGIQUE</strong> <!-- Texte en gras -->- SAINT JEAN-BAPTISTE DE LA SALLE (Juillet 2024)
                        <p>Baccalaur&eacute;at Technologique en Sciences et Technologies de l&#39;Industrie et du D&eacute;veloppement Num&eacute;rique.</p>
                    </li>
                </ul>
            </section>
            <section class="benevolat"  id="benevolat"> <!-- Section benevolat -->
                <h2>B&#201;N&#201;VOLAT</h2> <!-- Titre 2-->
                <ul>
                    <li>
                        <strong>PROJET PHONE-BOX</strong> <!-- Texte en gras --> (Septembre 2023 - Juin 2024)
                        <p>Coffre-fort pour t&eacute;l&eacute;phones, int&eacute;grant un syst&egrave;me de s&eacute;curit&eacute; avec digicode.</p>
                    </li>
                    <li>
                        <strong>PROJET PET-SEC</strong> <!-- Texte en gras --> (F&eacute;vrier 2023 - Mai 2023) 
                        <p>Conception d&#39;une liti&egrave;re pour chat auto-nettoyante.</p>
                    </li>
                    <li>
                        <strong>PROJET PUISSANCE 4</strong> <!-- Texte en gras --> (Octobre 2022 - Janvier 2023)
                        <p>Conception d&#39;un syst&egrave;me de jeu interactif avec compteur &eacute;lectronique int&eacute;gr&eacute;.</p>
                    </li>
                </ul>
            </section>
        </div>
    </div>
    <footer class="footer"> <!-- Pied de page -->
        <p>Email : <a href="mailto:luxcome2@gmail.com">luxcome2@gmail.com</a></p> <!-- Lien mailto pour envoyer un email -->
        <p>Adresse : 8 Rue de la Maladrie, 51490 Beine-Nauroy</p> <!-- Adresse de contact -->
        <p>T&eacute;l&eacute;phone : +33 6.89.98.06.53</p> <!-- Numero de telephone -->
        <p><a href="https://www.linkedin.com/in/c&ocirc;me-lux">Mon LinkedIn</a></p> <!-- Lien vers le profil LinkedIn -->
        <p>&copy; 2024 C&#244;me Lux. Tous droits r&eacute;serv&eacute;s.</p> <!-- Mention legale et droits d'auteur -->
    </footer>
</body>
</html>
