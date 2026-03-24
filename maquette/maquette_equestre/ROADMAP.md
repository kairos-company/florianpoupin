# Roadmap maquette index.html

## Footer -- À REPRENDRE
- Logo complet (LogoFinalFP-12.png) en place, mais à finaliser :
  - Réduire la taille du logo (30rem = trop grand)
  - Ajouter une 4e colonne de liens (contenu à définir)
  - Réduire l'espace vide bordeaux au-dessus de l'alignement logo/texte
  - Alignement vertical logo / colonnes de texte à ajuster
- Fichier source logo : `images/Equestre/LOGOFP/PNG/LogoFinalFP-12.png` (RGBA, fond transparent)

## Académie -- Restructuration de la page
- Le bloc Académie (3 arts + formules + déroulé journée + infos pratiques) est un pavé monolithique
- À restructurer en sections élégantes :
  - Les 3 arts (équitation, escrime, danse) : déjà en blocs séparés, OK
  - La section "Deux formules" : séparer visuellement les 2 académies (Pluvinel / La Broue)
  - Le déroulé de la journée : transformer en timeline verticale élégante ou tableau stylisé
  - Les infos pratiques (déplacements, structure d'accueil) : encart dédié, pas mélangé avec le déroulé
- Photos mises à jour : hero, escrime, danse

## Home -- Disciplines
- Remplacer la carte Fauconnerie (04) par une discipline équestre (à définir avec Florian)

## P0 -- Bloquants identifiés
- Menu hamburger mobile absent (header-nav display:none sous 768px)
- Lien cassé : `href="academie.htmlsalomon-de-la-broue/"` (ligne 1429)
- Image manquante : `la-cabriole-saumur.webp` (fond section formations)

## Témoignages
- Passer l'autoplay de 8s à 12s (conserver sélection manuelle par dots)

## P1 -- Importants
- Poids images non optimisé (apropos.png 6,4 Mo, cat-travail-pied.jpg 17 Mo)
- 11 dots témoignages illisibles, pagination à revoir
- Liens mixtes absolus/relatifs dans nav et footer (absolus cassés en statique)
- Grille disciplines déséquilibrée (carte grande trop haute)

## P2 -- Améliorations
- Pas de favicon ni theme-color
- Hero bouton bordeaux peu visible sur fond sombre
- Section CTA contact trop aérée
- Section zones d'intervention prévue mais absente
- OG image = nom Gemini, à remplacer
- Responsive tablette 1100px : grille disciplines bizarre
- `&` non encodé dans titre témoignages (ligne 1456)
- Carrousel sans prev/next, autoplay 8s
