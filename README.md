# smartuniv — L’atlas des cours

Carnet de révision de mes cours de BUT MMI (IUT Sénart-Fontainebleau) : une carte mentale des matières, avec, pour chaque cours, la lecture, une fiche, des quiz, des flashcards, des sujets notés, un mode oral et des exercices de code.

## Contenu

- `index.html` : le site, en un seul fichier (HTML, CSS et JS).
- `data/courses.json` : les matières et les cours (importés de Notion).

## Utilisation

Le site complet tourne sur claude.ai, où il a accès à Claude, à Notion et à une base de données.

Ouvert ailleurs (GitHub Pages, serveur local), seule la lecture fonctionne : carte, cours, recherche, chronologie, glossaire et filtre par parcours. Les quiz, fiches, flashcards générées, l’oral, l’import Notion, l’enregistrement des cours et les échéances partagées ont besoin de claude.ai.

Pour le tester en local :

```bash
python3 -m http.server
```

puis ouvrir http://localhost:8000.
