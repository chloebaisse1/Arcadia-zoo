# ZOO ARCADIA

Creation application web pour le ZOO Arcadia

# Pre requis

- IDE ou application de traitement de texte
- Connexion internet
- Compte GitHub ou en créer un
- Serveur local
- Node.js et NPM
- verifier l'installation avec la commande node --v
- verifier l'installation la commande npm --v
- Installation du framework Bootstrap ( facultatif)
- MySQL/ MariaDB/ PostGreSQL (base de donnée relationnelle)

# Installation

# Démarrage

- creation d'un dossier avec le nom du projet sur votre PC
- Ouvrir le dossier dans un editeur de code ( VSCODE ici)
- creation fichier index.html qui contiendra :
    - le header et le footer de la page
- creation d'un fichier Readme.md pour expliquer les etapes
- connexion/inscription a GitHub l'extension GitHub
- Creation d'un repository sur GitHub
- Apres chaque installations d'extensions et/ou chaque créations de pages ou dossiers,
  effectuer un commit & push afin de sauvegarder son travail pour eviter de perdre le contenu (beug)
-> (Onglet source controle)
- Mettre un message de COMMIT ( message de validation qui explique les modifications effectuées)
  (le COMMIT doit etre clair dans les explications)

- Effectuer un COMMIT & push pour pouvoir interagir avec le depot distant ( Repository sur GitHub)

# Creation dossier Router avec :

- 1 fichier allRoutes.js ( contient toutes les routes de l'application, et définit aussi la variable websiteName qui representera le nom de l'application web)
- 1 fichier Routes.js ( définit une classe Route qui répresente une route de l'application)
  Chaque route possède une URL, un chemin vers un fichier HTML, un titre, et un chemin vers un fichier JavaScript (facultatif))
- 1 fichier Router.js ( importe la classe Route et les variables " AllRoutes.js" et "WebsiteName" du fichier AllRoutes.js. Il contient la logique de routage)

# Contenu de mon site :

- page index.html avec le contenu de mon site
- page Home.html qui sera la page d'accueil

- 1 dossier Pages avec a l'interieur :
- page habitats ( vue globale qui references les 3 habitats)
- page services (descriptions des differents services proposés)
- page avis (formulaire)
- page contact (formulaire)
- page de connexion

a l'interieur du dossier pages j'ai egalement cration d'un autre dossier concernant les habitats ( 1 page par habitats)

- Jungle
- Marais
- Savane

- Dossier Auth a l'interieur du dossier Pages avec :

- espace admin
- espace connexion
- espace veterinaire
- espace employé

- un dossier images contenant toutes les images de mon site.

- Un dossier scss qui contient :
- custom.scss qui contient mes couleurs defini depuis mes maquettes
- mon fichier main.scss qui contient toutes les mises en pages/formes du contenu de mon application ( couleurs, taille, disposition, icones....)

- Un dossier javascript qui contient :
  - fichier scrpit.js avec formulaire de connexion/tests
  - dossier auth :
    -> admin.js
    -> employe.js
    -> veterinaire.js
    -> connexion.js
    
- Un dossier Documents qui contient :
- mes diagrammes
- mes Mockup et Wireframes
- ma charte graphique

- Un dossier SQL qui contient :
  - creation base de donnée + tables

# Fabriqué avec :

Boostrap / Boostrap icons ( framework front end)
mise en page, images et couleurs avec du CSS
MySQL (base de données back end)
Deploiement de la partie FRONT END avec AlwaysData et FileZilla

# versions

bootstrap & bootstrap icons 5.3.3
php 8.3.6
npm 10.5.0
node.js 20.12.2
MySQL 8.2
