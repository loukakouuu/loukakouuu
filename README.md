## 👋

Ce qui m'intéresse : les systèmes qui transforment de la donnée brute en
quelque chose dont on peut tirer une décision — et, accessoirement, les
systèmes qui simulent quelque chose.

---

### 📊 Esports Data Platform

Une chaîne de données complète sur l'esport professionnel, de l'ingestion
jusqu'à la prédiction.

L'esport publie beaucoup de données, mais éclatées : chaque discipline a ses
sources, ses formats et ses quotas, et aucune ne parle à l'autre. Le projet les
réconcilie dans un modèle commun, puis s'en sert.

- **Ingestion** — collecte incrémentale et idempotente sur trois sources aux
  schémas, authentifications et quotas différents
- **Transformation** — normalisation inter-disciplines avec dbt, tests de données
- **Analyse & modélisation** — exploration du circuit, puis prédiction de
  résultats avec validation temporelle

`Python` · `DuckDB` · `dbt` · `pandas` · `scikit-learn`

→ **[Voir le projet](https://github.com/loukakouuu/esports-data-platform)** *(en construction)*

---

### 🎮 Esport Manager

Un jeu de gestion d'équipe esport développé sous **Godot / GDScript**. Pas un
clicker : une simulation où l'on dirige une structure, négocie les contrats et
voit les décisions se répercuter saison après saison.

- **Architecture modulaire par discipline** — un registre de modules permet
  d'ajouter un jeu (Valorant, CS2) sans toucher au moteur commun
- **Moteur de simulation** — génération de saisons, formats de tournois,
  progression des joueurs, marché des transferts
- **Sa propre chaîne de données** — import, modélisation et validation des
  équipes et effectifs réels
- **566 vérifications automatisées** sur 42 suites de tests

→ **[Voir le projet](https://github.com/loukakouuu/esport-manager)**

---

### 🛠️ Compétences

**Data** · Python · SQL · pandas · DuckDB · dbt · scikit-learn
**Qualité & CI/CD** · Jenkins · SonarQube · pytest · tests unitaires, intégration et données · TDD
**Autres langages** · GDScript · Java · JavaScript
**Outils** · Git · Docker

---

### 📚 Travaux académiques

Projets réalisés en formation, gardés publics parce que la démarche y est
documentée :

| Projet | Sujet |
|---|---|
| [TP-shopflow-testing-cicd](https://github.com/loukakouuu/TP-shopflow-testing-cicd) | Chaîne de tests complète sur une API Python : unitaires, intégration, TDD, performance, sécurité |
| [TP-fastapi-devops-pipeline](https://github.com/loukakouuu/TP-fastapi-devops-pipeline) | API FastAPI avec pipeline Jenkins et audit SonarQube |
| [TP-shuttle-code-audit](https://github.com/loukakouuu/TP-shuttle-code-audit) | Audit qualité et remédiation sur une base Android legacy *(code applicatif tiers)* |
| [TP-mvc-vanilla-js](https://github.com/loukakouuu/TP-mvc-vanilla-js) | Patron MVC implémenté en JavaScript natif |
