# Instructions pour la Création d'une Page Minecraft avec Bootstrap

## Structure de Base HTML

Utilisez le fichier `index.html` de base avec les éléments suivants :

- **DOCTYPE** : `<!DOCTYPE html>`
- **HTML** : `<html lang="fr">`
- **Head** : Contient les métadonnées, le titre, et les liens vers les feuilles de style Bootstrap et vos fichiers CSS.
- **Body** : Contient tout le contenu visible de votre page.

## Balises Sémantiques

Utilisez des balises sémantiques pour structurer votre contenu de manière significative :

- **`<header>`** : En-tête de la page ou d'une section.
- **`<nav>`** : Section de navigation.
- **`<main>`** : Contenu principal de la page.
- **`<section>`** : Section générique pour regrouper du contenu.
- **`<footer>`** : Pied de page.

## Navbar

Utilisez la classe `navbar` pour créer une barre de navigation en haut de la page. Voici quelques classes utiles :

- **`navbar-expand-lg`** : Rend la navbar réactive.
- **`bg-danger`** : Définit la couleur de fond.
- **`sticky-top`** : Garde la navbar en haut de la page lors du défilement.
- **`navbar-toggler`** : Bouton pour les menus mobiles.
- **`collapse navbar-collapse`** : Conteneur pour les liens de navigation qui s'effondrent sur mobile.

## Carousel

Utilisez la classe `carousel slide` pour créer un carousel d'images. Voici quelques classes et attributs utiles :

- **`carousel-indicators`** : Ajoute des indicateurs pour le carousel.
- **`carousel-inner`** : Conteneur pour les éléments du carousel.
- **`carousel-item`** : Chaque élément du carousel.
- **`carousel-caption`** : Légende pour chaque élément du carousel.
- **`carousel-control-prev` et `carousel-control-next`** : Contrôles pour naviguer entre les éléments du carousel.

## Sections et Conteneurs

Utilisez des conteneurs et des rangées pour structurer votre contenu :

- **`container`** ou **`container-fluid`** : Conteneurs pour le contenu.
- **`row`** : Rangées pour organiser les colonnes.
- **`col-lg-*`** : Colonnes pour organiser le contenu horizontalement.


```html
<!-- Exemple de grid Bootstrap -->
<section class="container">
  <!-- Rangée -->
  <div class="row">
    <!-- colonne -->
    <div class="col-lg-4">
      Column #1
    </div>
    <!-- colonne -->
    <div class="col-lg-4">
      Column #2
    </div>
    <!-- colonne -->
    <div class="col-lg-4">
      Column #3
    </div>
  </div>
</section>
```

## Classes de Spacing

Bootstrap offre des classes pour gérer les marges et les paddings :

- **`mt-*`** : Margin-top (par exemple, `mt-3` pour une marge supérieure de taille moyenne).
- **`mb-*`** : Margin-bottom.
- **`ms-*`** : Margin-start (left).
- **`me-*`** : Margin-end (right).
- **`pt-*`** : Padding-top.
- **`pb-*`** : Padding-bottom.
- **`ps-*`** : Padding-start (left).
- **`pe-*`** : Padding-end (right).
- **`py-*`** : Padding vertical (top et bottom).
- **`px-*`** : Padding horizontal (start et end).

```html
<!-- Exemple sur une section -->
<section class="container-fluid py-5">
  <!-- Contenu HTML -->
</section>

<!-- Exemple sur une balise <p> -->
<p class="mt-3">Paragraphe avec du margin-top</p>
```

## Alignement de Texte

Pour aligner le texte, utilisez les classes suivantes :

- **`text-center`** : Centre le texte.
- **`text-start`** : Aligne le texte à gauche.
- **`text-end`** : Aligne le texte à droite.

```html
<!-- Exemple -->
<p class="text-center">Paragraphe centré</p>
```

## Flexbox

Utilisez la class `d-flex` sur une `div` ou une `section` pour déclarer une flexbox avec Bootstrap.
Vous pouvez ensuite utilisez les class de flex, par exemple `justify-content-center`, `flex-column`, `align-items-center`, etc pour aligner correctement vos contenus HTML.

```html
<!-- Exemple -->
<section class="container d-flex align-items-center justify-content-center">
  <!-- Contenu parfaitement centré -->
</section
```

## Images et Vidéos

- **Images** : Utilisez la classe `img-fluid` pour que les images s'adaptent à la largeur de leur conteneur.
- **Vidéos** : Utilisez des `iframe` pour intégrer des vidéos YouTube. Assurez-vous d'utiliser des classes de responsive design pour les rendre adaptées à toutes les tailles d'écran.
