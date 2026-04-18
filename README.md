# Mon Budget

PWA de gestion de budget personnel — React + Firebase + Tailwind, single-file.

🔗 **Application en ligne** : https://azizndoumbe.github.io/app-mon-budget/

## Fonctionnalités

- Tableau de bord responsive (desktop + mobile) avec solde courant, avant-salaire, patrimoine total, santé budget IA
- Suivi des dépenses par catégorie personnalisable (budget, couleur, emoji)
- Objectifs d'épargne avec liaison automatique aux catégories du même nom
- PEA & Crypto avec projections long terme (taux 7 % / 15 %), total versé, plus-value, date de dernière mise à jour
- Charges fixes + abonnements automatiques
- Analyse IA des dépenses (détection livraisons, achats compulsifs, patterns récurrents)
- Export CSV, mode sombre, masquage des montants, PWA installable

## Stack

- React 18 (CDN) + Babel Standalone
- Tailwind CSS (CDN)
- Firebase Auth (Google) + Firestore
- Chart.js 4.4
- Inter + Plus Jakarta Sans (Google Fonts)

## Déploiement

GitHub Pages — auto-deploy à chaque push sur `main`.

## Développement

Ouvrir `index.html` dans un navigateur. Aucun build, aucune dépendance locale.
