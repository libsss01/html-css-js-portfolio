# HTML CSS JS Portfolio

Ce depot contient un portfolio personnel statique realise avec HTML, CSS et JavaScript. Il presente le profil de Mame Libasse Laye Sylla, ses competences, son parcours, ses projets et ses informations de contact.

## Probleme resolu

Un portfolio permet de regrouper dans une seule page les informations importantes d'un profil developpeur : presentation, competences, experience, projets, CV, GitHub, LinkedIn et contact. Ce projet sert aussi de pratique concrete pour construire une interface responsive avec HTML, CSS et JavaScript sans framework.

## Fonctionnalites

- Navigation desktop avec ancres vers les sections de la page.
- Menu hamburger pour les ecrans mobiles.
- Section profil avec nom, role, CV, contact et liens sociaux.
- Section "About Me" avec experience et formation.
- Section experience avec competences frontend, backend et langages.
- Section projets avec cartes et boutons GitHub / Live Demo.
- Section contact avec email et LinkedIn.
- Transitions CSS et mise en page responsive via media queries.

## Stack technique

- HTML5
- CSS3
- JavaScript vanilla
- Google Fonts avec la police Poppins

## Structure du projet

```txt
html-css-js-portfolio/
|-- index.html          # Structure de la page
|-- style.css           # Styles principaux
|-- mediacquires.css    # Media queries responsive
`-- script.js           # Ouverture/fermeture du menu mobile
```

## Assets attendus

Le fichier `index.html` reference plusieurs ressources locales dans un dossier `assests/` :

- Photo de profil
- CV PDF
- Icones LinkedIn, GitHub, email, education, experience
- Images de projets
- Icone de fleche

Si les images ou le CV ne s'affichent pas, verifier que le dossier `assests/` existe bien et que les noms de fichiers correspondent exactement aux chemins utilises dans `index.html`.

## Lancement local

Aucune installation n'est necessaire.

1. Cloner le depot :

```sh
git clone https://github.com/libsss01/html-css-js-portfolio.git
```

2. Ouvrir le fichier `index.html` dans un navigateur.

Vous pouvez aussi utiliser une extension comme Live Server dans VS Code pour profiter du rechargement automatique.

## Sections de la page

- `#profile` : introduction, CV et liens sociaux.
- `#about` : presentation personnelle.
- `#Experience` : competences techniques.
- `#Projects` : projets recents.
- `#Contact` : email et LinkedIn.

## Pistes d'amelioration

- Corriger les liens des projets avec les vrais depots et demos.
- Ajouter les assets manquants dans le depot.
- Harmoniser les noms de classes et corriger les petites fautes de texte.
- Ajouter une version anglaise/francaise si le portfolio vise plusieurs publics.
- Ajouter des balises meta SEO et Open Graph.
- Ajouter une section "Formation" dediee si le parcours doit etre plus visible.

## Auteur

Mame Libasse Laye Sylla
