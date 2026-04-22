# ⚡ Dashboard Marché de l'Emploi Tech & IA

> Une application web analytique permettant de visualiser les indicateurs clés du marché de l'emploi technologique mondial à travers des graphiques interactifs, une cartographie choroplèthe et des outils de comparaison multi-pays.

[![Demo](https://img.shields.io/badge/🔗_Démo_en_ligne-00d4ff?style=for-the-badge)](https://an-steve.github.io/Dashboard-Emploi-Tech/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/fr/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)](https://www.chartjs.org/)
[![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3.js&logoColor=white)](https://d3js.org/)

---

<img width="1903" height="535" alt="image" src="https://github.com/user-attachments/assets/d2d12718-0581-4705-9d85-35cd75f26497" />

---

##  À propos du projet

Ce dashboard analytique a été conçu pour explorer et visualiser les grandes tendances du marché de l'emploi dans les secteurs Tech & IA en 2024. Il permet d'analyser les données de salaires, les compétences les plus demandées, la répartition géographique des offres et de comparer les dynamiques entre pays.

**Sujet choisi pour sa forte pertinence :** le marché de l'emploi tech est l'un des secteurs les plus dynamiques de la décennie, porté par l'essor de l'IA générative, du cloud et de la data science.

---

##  Démo en direct

👉 **[Cliquez ici pour voir le Dashboard en ligne](https://an-steve.github.io/Dashboard-Emploi-Tech/)**

---

##  Fonctionnalités principales

###  Vue d'ensemble & KPIs
Affichage de 4 indicateurs clés animés : volume d'offres mondiales, salaire médian, postes IA ouverts et taux de chômage Tech. Graphique en anneau (Donut Chart) de la répartition par secteur et courbe d'évolution depuis 2019.

<img width="867" height="481" alt="image" src="https://github.com/user-attachments/assets/c139bac2-cc33-47ee-9df0-5998fc7a7dc1" />


###  Analyse des Salaires
Comparaison des rémunérations médianes par rôle Tech (horizontal bar chart), évolution salariale selon l'expérience (Junior → Lead), indice de progression salariale Tech vs autres secteurs, et répartition des avantages (télétravail, stock-options, formation…).

<img width="1776" height="572" alt="image" src="https://github.com/user-attachments/assets/25038143-dc45-44dd-9f3f-62d511f5e517" />

###  Carte des Compétences
Classement des technologies les plus demandées dans les offres d'emploi, croissance des offres liées à l'IA par framework (LLMs, MLOps, RAG…), et bubble chart croisant popularité d'un langage, salaire médian et volume d'offres.

<img width="1755" height="573" alt="image" src="https://github.com/user-attachments/assets/09169ff7-95b0-4544-83a3-de4bd1ac8cc0" />


###  Cartographie Mondiale Interactive
Carte choroplèthe développée avec **D3.js** et **TopoJSON** permettant de visualiser, pays par pays, le volume d'offres Tech, le salaire médian ou la croissance du marché. Système de tooltip au survol avec données détaillées.

<img width="1757" height="666" alt="image" src="https://github.com/user-attachments/assets/650a6083-6511-48e2-be94-2947f98c311b" />

###  Comparateur de Pays (Radar Chart)
Outil permettant de sélectionner jusqu'à 4 pays pour comparer leurs performances sur 6 dimensions : volume d'offres, niveau de salaire, croissance, formation Tech, innovation et attractivité du marché. Scatter plot corrélant offres et salaire par pays.

<img width="882" height="673" alt="image" src="https://github.com/user-attachments/assets/765f24ab-bfe7-442b-aa9c-f5ec2a56c7d9" />

---

##  Indicateurs suivis

| Indicateur | Unité | Description |
|---|---|---|
| **Volume d'offres Tech** | 000 postes | Nombre total d'offres d'emploi tech actives |
| **Salaire médian** | k€ / an | Rémunération médiane brute annuelle |
| **Croissance du marché** | % | Variation annuelle du nombre d'offres |
| **Taux de chômage Tech** | % | Taux de chômage dans les métiers tech |
| **Popularité des langages** | % | Fréquence d'apparition dans les offres |
| **Indice innovation** | /100 | Score composite de dynamisme tech du pays |

---

##  Technologies & Bibliothèques

| Technologie | Usage |
|---|---|
| **HTML5 / CSS3** | Structure, design responsive, mode sombre/clair automatique |
| **Vanilla JavaScript** | Logique métier, interactivité, filtres dynamiques |
| **Chart.js 4.4** | Graphiques : donut, line, bar (horizontal & vertical), bubble, radar |
| **D3.js v7** | Carte choroplèthe vectorielle mondiale |
| **TopoJSON 3** | Données géographiques optimisées pour la carte |
| **Google Fonts** | Typographies : Syne (titres) + DM Mono (données) |

---

##  Structure du projet

```
Dashboard-Emploi-Tech/
│
├── index.html          # Application complète (single-file)
└── README.md           # Documentation du projet
```

> Le projet est volontairement monofichier pour faciliter le déploiement sur GitHub Pages sans build step.

---

##  Installation rapide

1. **Clonez le dépôt :**
   ```bash
   git clone https://github.com/an-Steve/Dashboard-Emploi-Tech.git
   ```

2. **Ouvrez le fichier dans votre navigateur :**
   ```bash
   cd Dashboard-Emploi-Tech
   open index.html
   ```

> Aucune dépendance à installer, aucun serveur requis. Toutes les librairies sont chargées via CDN.

---

##  Déploiement sur GitHub Pages

1. Allez dans **Settings** → **Pages** de votre dépôt
2. Sélectionnez la branche `main` et le dossier `/ (root)`
3. Cliquez sur **Save** — le site sera accessible en quelques minutes

---

##  Sources de données

Les données utilisées sont à titre illustratif et s'appuient sur les rapports suivants :

- [LinkedIn Jobs Report 2024](https://economicgraph.linkedin.com/)
- [Stack Overflow Developer Survey 2024](https://survey.stackoverflow.co/2024/)
- [GitHub Octoverse 2024](https://octoverse.github.com/)
- [OCDE — Perspectives de l'emploi 2024](https://www.oecd.org/employment-outlook/)
- [Eurostat — ICT Specialists 2024](https://ec.europa.eu/eurostat/)

---

##  Choix de design

- **Thème dark par défaut** avec bascule clair/sombre
- **Palette cyberpunk** : cyan `#00d4ff`, violet `#7c3aed`, vert émeraude `#10b981`
- **Grille de fond** animée pour renforcer l'esthétique data
- **Typography duale** : Syne (display) + DM Mono (données) pour une lisibilité optimale
- **Animations d'entrée** en cascade sur les KPI cards

---

##  Licence

Ce projet est open-source sous licence [MIT](LICENSE).

---

**Réalisé par [ANTON NELCON Steve](https://github.com/an-Steve)**
