---
layout: default
title: "Élodie HEINRY | Data Analyst"
description: "Nouvelle direction, Même détermination !"
---
<style>
/* --- Variables & Reset --- */
:root { --primary-color: #1abc9c; --secondary-color: #159957; }
* { box-sizing: border-box; margin: 0; }
html { scroll-behavior: smooth; }
body { font-family: sans-serif; line-height: 1.6; color: #333; }

/* --- Utilitaires --- */
.text-center { text-align: center; }
.mb-1 { margin-bottom: 1rem; } .mb-2 { margin-bottom: 2rem; } .mb-3 { margin-bottom: 3rem; }
.mt-1 { margin-top: 1rem; } .mt-2 { margin-top: 2rem; }
.section-padding { padding: 3rem 1rem; }
.container { max-width: 900px; margin: 0 auto; padding: 0 1rem; }

/* --- Composants --- */
/* Photo */
.profile-photo {
    width: 200px; height: 200px; border-radius: 50%; object-fit: cover;
    display: block; margin: 0 auto 2rem;
}
/* Boutons & Liens */
.btn {
    display: inline-block; padding: 0.6rem 1.4rem; margin: 0.25rem;
    background: var(--primary-color); color: white;
    text-decoration: none; border-radius: 5px; border: none;
    font-size: 1rem; cursor: pointer;
}
.btn-secondary {
    background: #f5f5f5; color: var(--primary-color);
    border: 1px solid var(--primary-color);
}
/* Icônes de contact */
.contact-icons { text-align: center; margin: 2rem 0; }
.icon-link {
    display: inline-flex; justify-content: center; align-items: center;
    width: 60px; height: 60px; border-radius: 50%;
    background: var(--primary-color); margin: 0.5rem;
    text-decoration: none; transition: opacity 0.3s;
}
.icon-link:hover { opacity: 0.8; }
.icon-link img { width: 30px; height: 30px; }
/* Navigation */
.main-nav { text-align: center; margin: 2rem 0; }
/* Séparateurs */
.section-separator {
    border: none; border-top: 2px solid var(--primary-color);
    margin: 2rem auto; width: 80%;
}
/* Cartes de projet */
.project-card {
    border: 1px solid; border-radius: 10px; padding: 1.5rem;
    background: #f8f9fa; margin-bottom: 2rem;
}
.project-card h3 { margin-top: 0; margin-bottom: 0.5rem; }
.project-card h3 img { height: 1.5em; vertical-align: middle; margin-right: 0.5rem; }
.skill-tag {
    display: inline-block; background: #555; color: white;
    padding: 0.3rem 0.8rem; border-radius: 15px; font-size: 0.9rem;
    margin: 0.25rem;
}
/* Tableau "Ce qui me définit" */
.qualities-table {
    border-collapse: collapse; border: none; margin: 1rem auto;
}
.qualities-table td {
    text-align: center; padding: 0.3rem 0.5rem; border: none;
    white-space: nowrap;
}
.qualities-table td:first-child { text-align: right; }
.qualities-table td:last-child { text-align: left; }
/* Blocs de contenu */
.content-block {
    background: #f8f9fa; padding: 1.5rem; border-radius: 8px;
    margin-bottom: 1.5rem;
}
.timeline-section { border-left: 4px solid; padding-left: 1.5rem; margin-bottom: 2.5rem; }
</style>

<header class="text-center mb-3">
    <img src="assets/images/logo.png" alt="Portrait d'Élodie HEINRY" class="profile-photo">
    <h1>Élodie HEINRY | Data Analyst</h1>
    <p><strong>Rigueur scientifique • Esprit critique & analytique • Innovation • Collaboration • Autonomie</strong></p>
</header>

<!-- Accroche -->
<section class="text-center mb-3">
    <h2 style="color: var(--secondary-color);">De la Reconversion à la Révélation : Mon Pari Gagnant</h2>
</section>

<!-- Icônes de contact -->
<div class="contact-icons" role="group" aria-label="Contacts">
  <a href="mailto:heinryelodie@hotmail.fr" target="_blank" class="icon-link" title="Email">
    <img src="assets/images/email.png" alt="Icône email" >
  </a>
  <a href="https://www.linkedin.com/in/elodie-heinry" target="_blank" class="icon-link" title="LinkedIn">
    <img src="assets/images/in.png" alt="Icône LinkedIn">
  </a>
  <a href="https://github.com/Elo3534" target="_blank" class="icon-link" title="GitHub">
    <img src="assets/images/github.png" alt="Icône GitHub">
  </a>
  <a href="/assets/pdf/CV_Elodie_HEINRY.pdf" target="_blank" class="icon-link" title="Télécharger le CV">
    <img src="assets/images/cv.png" alt="Icône CV">
  </a>
  <a href="https://www.google.com/maps/place/Montpellier,+France" target="_blank" class="icon-link" title="Localisation">
    <img src="assets/images/localisation.png" alt="Icône localisation">
  </a>
</div>

<!-- Navigation -->
<nav class="main-nav" aria-label="Navigation principale">
  <a href="#apropos" class="btn">À Propos</a>
  <a href="#competences" class="btn">Compétences</a>
  <a href="#projets" class="btn">Projets</a>
  <a href="#formation" class="btn">Formation</a>
  <a href="#experiences" class="btn">Expériences</a>
  <a href="#contact" class="btn">Contact</a>
  <p class="mt-1"><strong>Disponible pour un CDI/CDD sur Montpellier et alentours</strong></p>
</nav>

<hr class="section-separator">

<!-- À propos -->
<section id="apropos" class="container section-padding">
  <header class="text-center mb-3">
    <h2>👋 À Propos de moi</h2>
  </header>
  <article class="text-center mb-3">
    <p class="mb-1">Je suis <strong>Data Analyst</strong>, avec un parcours scientifique axé sur l'analyse et l'expérimentation.<br>
    Je transforme la donnée en <strong>outils décisionnels simples, fiables, élégants, utiles et actionnables.</strong></p>
    <p class="mb-1">Avec deux reconversions réussies et une expérience scientifique solide en laboratoire, mon parcours démontre :</p>
    <ul style="display: inline-block; text-align: left;">
      <li>ma <strong>persévérance</strong> et ma <strong>motivation</strong> face aux défis complexes,</li>
      <li>ma <strong>forte capacité d'adaptation</strong> et <strong>d'apprentissage</strong>,</li>
      <li>ma <strong>curiosité intellectuelle</strong> toujours en éveil.</li>
    </ul>
  </article>

  <article class="text-center mb-3">
    <h3>🧩 Ce qui me définit</h3>
    <table class="qualities-table">
      <tbody>
        <tr><td><strong>Rigueur</strong></td><td>🎯</td><td><strong>Amélioration</strong></td></tr>
        <tr><td><strong>Analyse</strong></td><td>🔍</td><td><strong>Structuration</strong></td></tr>
        <tr><td><strong>Ingéniosité</strong></td><td>💡</td><td><strong>Sens pratique</strong></td></tr>
        <tr><td><strong>Visualisation</strong></td><td>📊</td><td><strong>Pédagogie</strong></td></tr>
        <tr><td><strong>Collaboration</strong></td><td>🤝</td><td><strong>Autonomie</strong></td></tr>
        <tr><td><strong>Adaptation</strong></td><td>💪</td><td><strong>Curiosité</strong></td></tr>
      </tbody>
    </table>
  </article>

  <article class="text-center mb-3">
    <h3>🚀 Ma valeur ajoutée</h3>
    <p class="mb-1">
      ✔ <strong>Définir une stratégie data</strong> alignée sur les objectifs métier et orientée vers la création de valeur.<br>
      ✔ <strong>Traduire des données complexes</strong> en insights clairs pour une prise de décision éclairée.<br>
      ✔ Allier <strong>expertise technique</strong> (SQL, Python, Power BI) et <strong>pédagogie</strong> pour autonomiser les équipes.<br>
      ✔ <strong>Concevoir et déployer</strong> des tableaux de bord et des outils d'aide à la décision fiables et évolutifs.<br>
      ✔ <strong>Garantir</strong> une rigueur analytique et méthodologique sur l'ensemble des processus.
    </p>
  </article>

  <article class="text-center mb-3">
    <h3>🌱 Ce que je recherche</h3>
    <p>Un poste de <strong>Data Analyst</strong> dans un <strong>environnement exigeant</strong> où la data est au cœur de la stratégie.<br>
      Je souhaite m'investir dans des projets <strong>concrets</strong>, à <strong>fort impact</strong>, alliant <strong>logique</strong>, <strong>innovation</strong> et <strong>travail d'équipe.</strong></p>
  </article>

  <article class="text-center">
    <h3>📌 Ma méthodologie</h3>
    <p>
      <strong>Comprendre le besoin</strong><br>↓<br>
      <strong>Analyser les données</strong><br>↓<br>
      <strong>Clarifier et transmettre les résultats</strong><br>↓<br>
      <strong>Proposer des actions</strong>
    </p>
  </article>
</section>

<hr class="section-separator">

<!-- Compétences -->
<section id="competences" class="container section-padding">
  <header class="text-center mb-3">
    <h2>🛠️ Compétences</h2>
    <p><em>Section en construction.</em></p>
  </header>
</section>

<hr class="section-separator">

<!-- Projets -->
<section id="projets" class="container section-padding">
  <header class="text-center mb-3">
    <h2>🚀 Mes Projets Data</h2>
  </header>

  <!-- Projet 1 Netflix-->
  <article class="project-card" style="border-color: #e50914;">
    <h3 style="color: #e50914;">
      <img src="assets/images/netflix.png" alt="Logo Netflix">
      <strong>NETFLIX – Analyse stratégique → POWER BI & DAX – ONLYOFFICE</strong>
    </h3>
    <p>Création d'un <strong>dashboard interactif Power BI</strong> avec mesures <strong>DAX</strong> avancées via <strong>Power Query</strong> pour analyser la stratégie de contenu de Netflix.</p>
    <p><em><strong>Objectif métier :</strong> Décrypter la stratégie du géant du streaming pour créer l'engagement addictif de ses abonnés.</em></p>
    <div class="text-center">
      <span class="skill-tag" style="background: #e50914;">Power BI</span>
      <span class="skill-tag" style="background: #e50914;">DAX</span>
      <span class="skill-tag" style="background: #e50914;">Power Query</span>
      <span class="skill-tag" style="background: #e50914;">Data Modeling</span>
      <span class="skill-tag" style="background: #e50914;">Dashboard</span>
      <span class="skill-tag" style="background: #e50914;">Visualisation</span>
      <span class="skill-tag" style="background: #e50914;">Analyse exploratoire EDA</span>
    </div>
    <div class="text-center mt-1">
      <a href="https://github.com/Elo3534/NETFLIX_PowerBI_DAX_OnlyOffice" target="_blank" class="btn">
        👨‍💻 Voir le projet sur GitHub
      </a>
    </div>
  </article>

  <!-- Projet 2 IBM-->
  <article class="project-card" style="border-color: #4DA3FF;">
    <h3 style="color: #4DA3FF;">
      <img src="assets/images/ibm.png" alt="Logo IBM">
      <strong>ATTRITION CHEZ IBM – Analyse prédictive → Tableau & Python – Microsoft Power Point et Word</strong>
    </h3>
    <p><strong>Identification des drivers d'attrition</strong> grâce au <strong>feature engineering</strong>, à l'analyse exploratoire (<strong>EDA</strong>) et à la modélisation prédictive (<strong>Machine Learning</strong>).</p>
    <p><em><strong>Objectif métier :</strong> Déterminer les facteurs-clés influençant le turnover et fournir des insights actionnables pour anticiper la rétention des talents.</em></p>
    <div class="text-center">
      <span class="skill-tag" style="background: #4DA3FF;">Machine Learning</span>
      <span class="skill-tag" style="background: #4DA3FF;">Feature Engineering</span>
      <span class="skill-tag" style="background: #4DA3FF;">Analyse Prédictive</span>
      <span class="skill-tag" style="background: #4DA3FF;">Analyse exploratoire EDA</span>
      <span class="skill-tag" style="background: #4DA3FF;">Tableau</span>
      <span class="skill-tag" style="background: #4DA3FF;">Python</span>
      <span class="skill-tag" style="background: #4DA3FF;">Microsoft Office</span>
    </div>
    <div class="text-center mt-1">
      <a href="https://github.com/Elo3534/Attrition-IBM_Tableau_Python_Word" target="_blank" class="btn">
        👨‍💻 Voir le projet sur GitHub
      </a>
    </div>
  </article>

  <!-- Projet 3 Tinder (incomplet) -->
  <article class="project-card" style="border-color: #FF4B91; opacity: 0.7;">
    <h3 style="color: #FF4B91;">
      <img src="assets/images/tinder.png" alt="Logo Tinder">
      <strong>TINDER – Analyse inférentielle → Python (Projet en cours)</strong>
    </h3>
    <p><em>Description à venir.</em></p>
  </article>

</section>

<hr class="section-separator">

<!-- Formations -->
<section id="formation" class="container section-padding">
  <header class="text-center mb-3">
    <h2>🎓 Formations & Certifications</h2>
  </header>

  <div class="timeline-section" style="border-color: #1F77B4;">
    <h3 style="color: #1F77B4;">📈 Parcours DATA</h3>
    <div class="content-block">
      <h4>🎓 <strong>CONCEPTION ET DÉVELOPPEMENT EN SCIENCES DE DONNÉES (CDSD)</strong></h4>
      <p><strong>Montpellier — 2025</strong></p>
      <p>Analyse exploratoire, descriptive et inférentielle de données. Direction de projets de gestion de données.</p>
      <p>Titre professionnel de niveau bac +4 (RNCP). Formation en <strong>Bootcamp : FULLSTACK DATA ANALYSIS</strong> chez Jedha Academy.</p>
    </div>
    <h4 style="color: var(--primary-color);">🏅 Certifications Editeurs</h4>
    <p>Google Analytics 4 (GA4) — 2025<br>Hubspot CMR for Marketers — 2025</p>
  </div>

  <div class="timeline-section" style="border-color: #3498db;">
    <h3 style="color: #3498db;">🔬 Parcours SCIENCES</h3>
    <div class="content-block">
      <h4>🎓 <strong>LICENCE PROFESSIONNELLE Biologie Analytique et Expérimentale (BAEMOVA)</strong></h4>
      <p><strong>Angers — 2010</strong></p>
    </div>
    <div class="content-block">
      <h4>🎓 <strong>DUT GENIE BIOLOGIQUE en Analyses Biologiques et Biochimiques (ABB)</strong></h4>
      <p><strong>Clermont-Ferrand — 2009</strong></p>
    </div>
  </div>

  <div class="timeline-section" style="border-color: #9b59b6;">
    <h3 style="color: #9b59b6;">💪 Reprise d'étude</h3>
    <div class="content-block">
      <h4>🎓 <strong>Licence Biologie Première Année</strong></h4>
      <p><strong>Rennes — 2007</strong></p>
      <p><em>"J'ai voulu évaluer mes capacités d'apprentissage avant de me lancer dans une formation diplômante."</em></p>
      <p>✅ Année validée - Admissible en L2</p>
    </div>
    <div class="content-block">
      <h4>🎓 <strong>DAEU B (Diplôme d'Accès aux Études Universitaires)</strong></h4>
      <p><strong>Rennes — 2006</strong></p>
    </div>
  </div>
</section>

<hr class="section-separator">

<!-- Expériences -->
<section id="experiences" class="container section-padding">
  <header class="text-center mb-3">
    <h2>🤝 Expériences Professionnelles</h2>
  </header>

  <div class="timeline-section" style="border-color: #3498DB;">
    <h3 style="color: #3498DB;">🔬 Expériences en Laboratoire</h3>
    <div class="content-block">
      <h4>AGENT DE MAÎTRISE en laboratoires de sciences</h4>
      <p><strong>2017 - Lycée privé – Aix-en-Provence - 7 ans</strong></p>
      <p><strong>Mission :</strong></p>
      <ul>
        <li>Référencement des produits chimiques (Intégration d'un outil informatisé)</li>
        <li>Mise en sécurité des laboratoires, gestion du budget et du matériel</li>
        <li>Aide à la préparation des TP et mise au point des protocoles expérimentaux</li>
      </ul>
    </div>
    <div class="content-block">
      <h4>INGÉNIEURE D'ÉTUDE en cytogénétique</h4>
      <p><strong>2010 - INRAE - Angers - 3 ans</strong></p>
      <p><em>Analyse cytogénétique de 8 genres de plantes ornementales pour un projet partenarial.</em></p>
      <p><strong>Mission :</strong></p>
      <ul>
        <li>Conception et mise au point de protocoles de cytogénétique moléculaire et de cytométrie de flux</li>
        <li>Analyses statistiques inférentielles, étude bibliographique, synthèses</li>
        <li>Présentation régulière des résultats avec supports visuels en comités techniques (16 fois/an)</li>
        <li>Collaboration avec équipes pluridisciplinaires et partenaires externes</li>
      </ul>
      <p><strong>Réalisations marquantes :</strong></p>
      <ul>
        <li>Mise en place, maintenance et formation complète sur un cytomètre en flux et en microscopie à fluorescence</li>
        <li>Organisation des laboratoires : manuels utilisateurs, formation, gestion des stocks et budgets</li>
        <li>Participation à des conférences internationales (Prague 2012, Paris 2011, Montpellier 2010)</li>
      </ul>
    </div>
  </div>

  <div class="timeline-section" style="border-color: #FF8C00;">
    <h3 style="color: #FF8C00;">🏭 Expériences en industrie</h3>
    <div class="content-block">
      <h4>CONDUCTRICE DE LIGNES automatisées et OPÉRATRICE de fabrication</h4>
      <p><strong>2002-2017 - Ipsen BioPharma — Valeo — Canon — Thalès Microelectronics — Oberthur Card Systems</strong></p>
      <ul>
        <li>Conduite de lignes automatisées et semi-automatisées (secteurs militaire, médical, bancaire)</li>
        <li>Contrôle qualité et respect des procédures (secteur militaire et pharmaceutique)</li>
        <li>Polyvalence et adaptation à différents environnements industriels</li>
      </ul>
    </div>
  </div>
</section>

<hr class="section-separator">

<!-- Contact -->
<section id="contact" class="container section-padding text-center">
  <header class="mb-3">
    <h2>📫 Contactez-moi</h2>
  </header>
  <div style="display: inline-block; text-align: left;">
    <p>📧 <a href="mailto:heinryelodie@hotmail.fr">heinryelodie@hotmail.fr</a></p>
    <p>📞 06 18 70 42 77</p>
    <p>💼 <a href="https://www.linkedin.com/in/elodie-heinry" target="_blank">Mon LinkedIn</a></p>
    <p>👨‍💻 <a href="https://github.com/Elo3534" target="_blank">Mon GitHub</a></p>
    <p>🌐 Montpellier</p>
  </div>
</section>

<hr class="section-separator">

<!-- À propos personnel -->
<section class="container section-padding text-center">
  <header class="mb-3">
    <h2>👁️ Vous vouliez en savoir plus ?</h2>
  </header>
  <article style="max-width: 700px; margin: 0 auto;">
    <p><strong>🎮🎯 L'Experte en énigmes tordues</strong> - Mon cerveau adore les défis qui se terminent par un 'EURÊKA !'</p>
    <p><strong>🌿🐾 L'Émerveillée</strong> - La nature est ma source d'inspiration préférée.</p>
    <p><strong>✈️🧳 L'Aventurière</strong> - Mon passeport a plus de tampons que mon carnet de notes.</p>
    <p><strong>💦💧 La Sirène</strong> - Si on me cherche, checkez les plans d'eau.</p>
    <p><strong>💬🤝 La Social Butterfly</strong> - Une bonne conversation, des fous rires... c'est mon carburant social.</p>
    <p><strong>📚 La Curieuse Littéraire</strong> - Entre deux datasets, mon esprit s'évade dans les enquêtes policières et le journalisme d'investigation.</p>
    <p><strong>🔧🔨 La Bricoleuse Philosophe</strong> - Mes mains aiment créer pendant que mon cerveau déconstruit les problèmes.</p>
    <p class="mt-2">En résumé : <strong>100% curieuse</strong>, <strong>0% routine</strong>, et un <strong>grand sourire</strong> face aux défis !</p>
  </article>
</section>

<!-- Pied de page unifié -->
<footer class="text-center section-padding">
  <a href="/assets/pdf/CV_Elodie_HEINRY.pdf" target="_blank" class="btn mb-2">📄 Téléchargez mon CV</a><br>
  <nav class="main-nav">
    <a href="#apropos" class="btn">À Propos</a>
    <a href="#competences" class="btn">Compétences</a>
    <a href="#projets" class="btn">Projets</a>
    <a href="#formation" class="btn">Formation</a>
    <a href="#experiences" class="btn">Expériences</a>
    <a href="#contact" class="btn">Contact</a>
  </nav>
  <div class="contact-icons mt-2">
    <a href="mailto:heinryelodie@hotmail.fr" target="_blank" class="icon-link" title="Email">
      <img src="assets/images/email.png" alt="Icône email" >
    </a>
    <a href="https://www.linkedin.com/in/elodie-heinry" target="_blank" class="icon-link" title="LinkedIn">
      <img src="assets/images/in.png" alt="Icône LinkedIn">
    </a>
    <a href="https://github.com/Elo3534" target="_blank" class="icon-link" title="GitHub">
      <img src="assets/images/github.png" alt="Icône GitHub">
    </a>
    <a href="/assets/pdf/CV_Elodie_HEINRY.pdf" target="_blank" class="icon-link" title="Télécharger le CV">
      <img src="assets/images/cv.png" alt="Icône CV">
    </a>
    <a href="https://www.google.com/maps/place/Montpellier,+France" target="_blank" class="icon-link" title="Localisation">
      <img src="assets/images/localisation.png" alt="Icône localisation">
    </a>
  </div>
  <p class="mt-2"><a href="#top" class="btn-secondary">↑ Haut de page</a></p>
</footer>
