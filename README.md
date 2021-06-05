# Evan Hoizey - B2A Info YNOV Paris

J'avais fait l'intégralité du projet en **SCSS** avec **GULP** et **browserSync**. 

Mais suite à l'effacement (imprévu en toute évidence) de *toutes* les données,
j'ai pu récupérer le **HTML** et le **CSS** des pages non rafraichies grâce à **browserSync** (suite à *5h* de recherches de code).

J'ai amélioré l'aspect du CSS avec un site de "**CSS Beautifuler**" car il s'était arrangé avec le SCSS de façon *optimisée mais difficilement lisible* (850 lignes condensées en ~130).

Je n'ai pas refait le SCSS comme je le voulais mais je peux prouver que j'ai utilisé SCSS avec des **enregistrements d'écran** que j'ai réalisés pendant le développement de la page.

J'ai, sinon, utilisé **JS** pour un *modal*, des pseudo-elements (**before**, **after**, **hover** et, il me semble, **nth-child**) et j'ai finalement utilisé des variables SCSS que je n'ai pas récupérées.

## **Les variables SCSS utilisées:**

**// les couleurs**

*$primary-color* et *$secondary-color*

*$light-gray* et *$dark-gray*

*$sand*

**// les polices**

*$primary-font* et *$secondary-font*

*$nav-font* et *$headings-font* (correspondant à '*$secondary-font*')

$*default-font* (correspondant à '*$primary-font*')

*$font-weight-default*

*$font-weight-secondary*

*$font-size-default*

## ***Les animations et effets réalisés***

### **Burger Button:**
* Un bouton n'affiché qu'en mobile et tablette verticale, utilisation du JS uniquement pour ajouter ou retirer une classe CSS faisant apparaître le menu pleine page
* Inversion des couleurs des textes au clic (au hover mais sur mobile cela équivaut à un focus)

### **Cards:**

* ***hover section:***
  * opacité des cartes à 50%
* ***hover card:***
  * opacité de la card à 100% et scale(1.1)

### **Textes:**

* **hover menus header:**
  * changement de couleur
* **hover 'Link__more':**
  * décalage animé de la flèche
* **hover menus footer:**
  * scale(1.1) -> J'aurais pu augmenter la font-size mais l'effet de décalage me plaisait bien

### **Boutons:**

* **hover:**
  * Changements de couleur
  
### **Section Jaguar+Whisky:**

* **hover:**
  * box-shadow apparaît de façon animée
