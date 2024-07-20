<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nos Moments Inoubliables Ensemble</title>
    <style>
        /* Vos styles CSS existants */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            background-image: url('file:///D:/redsite1/imgrom1.jfif') /* première image */;
			background-image: url('file:///D:/redsite1/imgrom2.jfif') /* deuxième image */;
			background-image: url('file:///D:/redsite1/imgrom3.jfif') /* troisième image */;
			background-size: contain;
			background-position: center;
			background-repeat: repeat
        }
        /* Styles pour le formulaire de connexion */
        #login-form {
            max-width: 400px;
            margin: 100px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        #login-form label {
            display: block;
            margin-bottom: 10px;
        }
        #login-form input[type="text"],
        #login-form input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        #login-form button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 4px;
            cursor: pointer;
        }
        #login-form button:hover {
            background-color: #555;
        }
        /* Styles pour le contenu principal */
        .container {
            max-width: 800px;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            display: none; /* Caché par défaut */
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 10px;
            margin-top: 20px;
        }
        .gallery img {
            width: 100%;
            border-radius: 8px;
        }
       @keyframes scintille {
			0% { opacity: 1; }
			50% { opacity: 0.2; }
			100% { opacity: 2; }
		}

		.texte-scintille {
			animation: scintille 3s infinite; /* Animation de scintillement pendant 2 secondes en boucle */
		}
		@keyframes defilement {
			0% { transform: translateY(0); }
			50% { transform: translateY(20px); }
			100% { transform: translateY(0); }
		}

		.element-defile1 {
			animation: defilement 3s ease-in-out infinite; /* Animation de défilement pendant 3 secondes en boucle */
		}
		@keyframes defilement {
			0% { transform: translateX(0); }
			50% { transform: translateX(20px); }
			100% { transform: translateX(0); }
		}

		.element-defile2 {
			animation: defilement 3s ease-in-out infinite; /* Animation de défilement pendant 3 secondes en boucle */
		}

		figure {
      margin-bottom: 20px; /* Espacement entre les figures */
    }
    figcaption {
      font-size: 18px; /* Taille de police pour la légende */
      margin-top: 10px; /* Espacement entre l'image et la légende */
	  font-weight: bold; /* Met le texte en gras */
	  color: blue; /* Change la couleur du texte */
    }
    </style>
</head>
<body>

<div id="login-form">
    <h2>Connexion requise</h2>
    <form id="loginForm">
        <label for="username">Nom d'utilisateur :</label>
        <input type="text" id="username" name="username" required>

        <label for="password">Mot de passe :</label>
        <input type="password" id="password" name="password" required>

        <button type="button" onclick="login()">Se connecter</button>
    </form>
</div>

<div class="container" id="main-content">
    <header>
        <h1>Nos Moments Inoubliables Ensemble</h1>
    </header>

    <section id="qui-sommes-nous">
        <h2 class="texte-scintille">Qui sommes-nous ?</h2>
        <p>Nous nous sommes rencontrés il y a près de 5 ans 7 et mois à [L'ENSTP].De cette rencontre est née une complicité evidente, un jeu de poursuite entre deux coeurs qui se cherche.
		   Depuis le premier jour de mon coeur tu as fait battre mon coeur sans meme te connaitre je savais que j'avais trouvé ma reine.
		   Audjourdhui te voici dans ma vie et je ne l'imagine plus sans toi ta présence est vitale.Je chérie chaque moment de puis le jour de notre rencontre juqu'au début de notre histoire
		   le 9 mars 2019.Bientot 5 ans 4 mois ensemble, 5 années mémorable,inoubliable, inestimable remplis de joie, d'amour,de haut, de bas et de tristesse.
		   Une rencontre entre un homme chanceux [Typhain] et une femme incroyablement extraordinaire [Laurette]</p>
    </section>

    <section id="galerie">
        <h2 class="texte-scintille">Galerie de Photos</h2>
        <div class="gallery">
            			<figure class="element-defile1">	
				<img src="file:///D:/redsite1/38.jpg" alt="Une femme unique d'une beauté à couper le soufle">
				<figcaption>Une femme unique d'une beauté à couper le soufle.</figcaption>
			</figure>
			<figure class="element-defile1">
				<img src="file:///D:/redsite1/39.jpg" alt="Rayonnante et belle">
				<figcaption>Rayonnante et belle.</figcaption>
			</figure>
			<figure class="element-defile1">
				<img src="file:///D:/redsite1/8.jpg" alt="Rayonnante et belle">
				<figcaption>Une femme incroyable au sourire angélique.</figcaption>
			</figure>
			<figure class="element-defile1">
				<img src="file:///D:/redsite1/13.jpg" alt="Rayonnante et belle">
				<figcaption>Ma douce et tendre praline d'amour.</figcaption>
			</figure>
			<figure class="element-defile1">
				<img src="file:///D:/redsite1/30.jpg" alt="Rayonnante et belle">
				<figcaption>Ma partenaire de vie.</figcaption>
			</figure>
			<figure class="element-defile1">
				<img src="file:///D:/redsite1/36.jpg" alt="Rayonnante et belle">
				<figcaption>Ma partenaire de travail.</figcaption>
			</figure>
			<figure class="element-defile1">
				<img src="file:///D:/redsite1/21.jpg" alt="Rayonnante et belle">
				<figcaption>L'ingénieur chargé des études de mon coeur.</figcaption>
			</figure>
			<figure class="element-defile1">
				<img src="file:///D:/redsite1/22.jpg" alt="Rayonnante et belle">
				<figcaption>Mon ame soeur.</figcaption>
			</figure>
        </div>
    </section>

    <section id="nos-aventures">
        <h2 class="texte-scintille">Nos Aventures</h2>
        <p>Nous avons partagé tant de moments inoubliables ensemble: ... (Votre contenu ici) ... </p>
        <div class="gallery">
            <figure class="element-defile2">	
				<img src="file:///D:/redsite1/1.jpg" alt="Une femme unique d'une beauté à couper le soufle">
				<figcaption>Moment spéciale à un évènement à l'ENSTP.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/2.jpg" alt="Rayonnante et belle">
				<figcaption>Une soirée inoubliable à YAFE avec ma moitié.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/3.jpg" alt="Rayonnante et belle">
				<figcaption>Une soirée inoubliable a PLAYCE avec mon amour je me souviens encore de ton sourire angelique ce jour.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/17.jpg" alt="Rayonnante et belle">
				<figcaption>Une séance de sport intense à l'ENSTP. Un moment magique car courir et transpirer à tes cotés était un véritable bonheur.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/23.jpg" alt="Rayonnante et belle">
				<figcaption>Un reveillon de noel réussi avec à mes coté la plus belle femme de la soirée.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/35.jpg" alt="Rayonnante et belle">
				<figcaption>Ton sourire éblouissant après une journée de travail ardu me rechauffe le coeur.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/20.jpg" alt="Rayonnante et belle">
				<figcaption>Une journée de balade et de travail avec ma merveilleuse femme.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/50.jpg" alt="Rayonnante et belle">
				<figcaption>Toujours avec ma partenaire de vie quelque soit l'évènement.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite/6.jpg" alt="Rayonnante et belle">
				<figcaption>A jamais toi et moi quelque soit la situation.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/10.jpg" alt="Rayonnante et belle">
				<figcaption>Je chérie a jamais chacun de nos moment à deux.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite/15.jpg" alt="Rayonnante et belle">
				<figcaption>Mon amour pour toi est sans limite. Je t'aime mon amour.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite/34.jpg" alt="Rayonnante et belle">
				<figcaption>Une séance au cinéma réussie avec mon ame soeur.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/14.jpg" alt="Rayonnante et belle">
				<figcaption>Monsieur et Madame en plein départ pour leur domicile après une journée de travail ardu.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/24.jpg" alt="Rayonnante et belle">
				<figcaption>Ton sourire est mon plus grand trésor.</figcaption>
			</figure>
			<figure class="element-defile2">
				<img src="file:///D:/redsite1/43.jpg" alt="Rayonnante et belle">
				<figcaption>Couple Goal de l'année 2024.</figcaption>
			</figure>
        </div>
    </section>

    <section id="ce-que-tu-representes">
        <h2 class="texte-scintille">Ce que tu représentes pour moi</h2>
        <p>Tu es ma source de bonheur quotidienne. Ta gentillesse, ton soutien et ton amour rendent chaque jour meilleur. Je suis reconnaissant de t'avoir dans ma vie.
		Tu es une gace et une bénédiction dans ma vie. Pardonne moi de ne pas etre l'homme dont tu peut etre toujours fière, pour chaque moment de doute de peine et de tristesse
		je te demande pardon. Tu es mon moteur et ma source d'inspiration mon amour pour toi me pousse chaque jour a me surpasser pour mériter ton pardon et te faire sourire.
		[Comme apprendre la programation pour t'exprimer mon amour digitalement].
		Tu représentes mon monde et mon univers. Sans toi je suis perdu et dérouter, je perd mes repères Je me sens comme vide sans toi. Tu es ma boussole, le soleil de ma vie
		qui m'éclaire dans mes moments les plus obscur.</p>
    </section>

    <footer style="text-align: center; margin-top: 20px;font-weight:bold;color=blue">
        <p>&copy; 2024 REDTYPH. Tous droits réservés.</p>
    </footer>
</div>

<script>
    function login() {
        var username = document.getElementById("username").value;
        var password = document.getElementById("password").value;

        // Vérifier les informations de connexion
        if (username === "Typhain" && password === "09012002") {
            // Afficher le contenu principal
            document.getElementById("login-form").style.display = "none";
            document.getElementById("main-content").style.display = "block";
        } else if (username === "Laurette" && password === "02012000") {
            // Afficher le contenu principal
            document.getElementById("login-form").style.display = "none";
            document.getElementById("main-content").style.display = "block";
        } else {
            // Afficher un message d'erreur
            alert("Nom d'utilisateur ou mot de passe incorrect.");
        }
    }
</script>

</body>
</html>
