# smartuniv — L’atlas des cours

Carnet de révision de mes cours de BUT MMI (IUT Sénart-Fontainebleau) : une carte mentale des matières, avec pour chaque cours la lecture, une fiche, un quiz, des flashcards, un sujet noté sur 20, un mode oral et des exercices de code.

## Contenu

- `index.html` : le site, en un seul fichier.
- `data/courses.json` : les matières et les cours.
- `data/generated.json` : fiches, quiz, flashcards, sujets avec corrigés, exercices et schémas déjà préparés.
- `media/` : images et PDF ajoutés depuis le site.

## Ajouter des cours depuis le site publié

Sur GitHub Pages, clique sur « Connexion GitHub » en haut du site et colle une clé d’accès (fine-grained token) limitée à ce dépôt, avec la permission « Contents : Read and write ». Les cours ajoutés ou modifiés sont alors enregistrés directement dans `data/courses.json`. La clé reste dans ton navigateur.

## Ce qui marche partout

Carte, cours, recherche, chronologie, glossaire, parcours Créa/Dév, fiches, quiz, flashcards, sujets avec auto-correction, oral avec réponses attendues, exercices JS exécutés dans la page, échéances et progression (gardées dans le navigateur).

Sur claude.ai en plus : génération de nouveaux contenus par Claude, correction des copies par Claude, import Notion, échéances partagées.

## Tester en local

```bash
python3 -m http.server
```

puis ouvrir http://localhost:8000.
