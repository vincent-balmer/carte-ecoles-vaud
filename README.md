# Carte des écoles – canton de Vaud

Carte interactive : **où ira mon enfant à l'école selon le village ?**

👉 **Ouvrir la carte : https://vincent-balmer.github.io/carte-ecoles-vaud/**

## Ce que fait la carte

- Tu cherches un village, une commune ou un NPA (ex. Bavois, 1372).
- La carte montre l'**école primaire** (1P-8P) en vert foncé et le **collège secondaire** (9S-11S) en vert clair.
- Une fiche donne l'adresse, le téléphone, le site web et la liste des bâtiments (collèges) de l'établissement.
- Le bouton « Tous les collèges » affiche les 508 bâtiments scolaires du canton.

Elle marche sur téléphone et sur ordinateur, sans rien installer.

## En chiffres

300 communes · 93 établissements · 8 régions scolaires · 462 localités / NPA · 508 collèges

## D'où viennent les données

- Répartition des communes : pages de la DGEO sur [vd.ch](https://www.vd.ch/def/dgeo/les-etablissements-scolaires) et directive 177 (2024) sur les aires de recrutement.
- Bâtiments scolaires : sites officiels de chaque établissement et [lausanne.ch](https://www.lausanne.ch) pour Lausanne.
- Données consultées en novembre 2026.

## Limites

- **Information indicative.** Les répartitions peuvent changer chaque année : vérifier auprès de l'établissement avant un déménagement.
- Les collèges sont placés au village (à Lausanne, au quartier), pas à l'adresse exacte.
- Dans les villes avec plusieurs établissements, la carte ne dit pas lequel correspond à quelle rue.
- Quelques années de classes manquent encore (Bex, Payerne-Granges, Renens, Blonay-Saint-Légier).

## Technique

Un seul fichier `index.html`, sans dépendance externe. Les données sont dans la balise `<script id="data">` (format JSON).
