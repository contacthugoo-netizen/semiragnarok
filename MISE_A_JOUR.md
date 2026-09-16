# Mise à jour RAGNARÖK — planning par équipe

## À faire (2 fichiers)

1. Remplace `index.html` à la racine du repo par celui de ce dossier.
2. Remplace `planning.xlsx` à la racine du repo par celui de ce dossier
   (c'est ton « Planning de Staff SEMI - Ragnarok_2.xlsx », juste renommé).
3. Commit + push → GitHub Pages se met à jour en 1–2 min.

Le `manifest.json` et le dossier `assets/` ne changent pas.

## Pour les prochaines modifs du planning

Édite le classeur dans Excel, enregistre, renomme la copie `planning.xlsx`, push.
L'app lit :
- **Paramètres** : le bloc ÉQUIPES (noms + chef d'équipe), la grille COMPOSITION DES ÉQUIPES
  (source de vérité pour l'équipe de chacun) et le tableau STAFF (téléphones).
- **Chaque onglet de jour** : la ligne d'en-tête « CRÉNEAU / PROGRAMME / Équipe 1…5 »,
  puis une ligne par créneau. Le texte de la case = la tâche affichée, telle quelle.
  « REPOS » (début de cellule) est affiché en grisé avec 😴.
  La colonne ÉQUIPES RÉVEILLÉES et les onglets Fiche / Récap sont ignorés.

Tout est repéré par les libellés, pas par les positions : tu peux ajouter des lignes,
renommer un poste, ajouter une 6e équipe (dans le bloc ÉQUIPES + une colonne dans la grille
et dans les jours) sans toucher au code.

⚠ Enregistre toujours depuis Excel (ou Numbers/LibreOffice) : l'app lit les valeurs
calculées des formules (en-têtes d'équipe, équipe auto). Un fichier généré par un script
sans recalcul afficherait des en-têtes vides — l'app retombe alors sur l'ordre des colonnes.
