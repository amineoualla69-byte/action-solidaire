# 🤝 Action! Solidaire — Tableau de bord d'engagement collaborateur

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge)
![Statut](https://img.shields.io/badge/statut-actif-brightgreen?style=for-the-badge)
![Missions](https://img.shields.io/badge/missions-47-purple?style=for-the-badge)
![Associations](https://img.shields.io/badge/associations-14-orange?style=for-the-badge)

**Outil de pilotage d'un programme d'engagement solidaire d'entreprise**  
Conçu dans le cadre de ma candidature au poste de *Chef de projet Engagement Solidaire* chez **TotalEnergies**.

[🌐 Dashboard Live](https://amineoualla.github.io/action-solidaire) · [📄 Docs](./docs/) · [📊 Données](./data/)

</div>

---

## 🎯 Contexte

Ce projet simule l'environnement de travail d'un Chef de projet Engagement Solidaire sur le périmètre **IDF + Nord France** :

| Périmètre | Valeur simulée |
|---|---|
| 👥 Collaborateurs couverts | 30 000 |
| 🔗 Réseau de référents | 30 (IDF + Nord) |
| 🏛️ Associations partenaires | 14 actives |
| 📋 Missions créées | 47 |
| ⏱️ Volume d'engagement | 24h / collaborateur / an |

---

## 📁 Structure du projet

```
action-solidaire/
├── index.html                   ← Dashboard interactif (aucune dépendance)
├── data/
│   ├── missions.json            ← Missions structurées (statut, région, BU…)
│   ├── associations.json        ← Partenaires ESS avec besoins et KPIs
│   ├── referents.json           ← Réseau des référents IDF/Nord
│   └── kpis.json                ← Indicateurs mensuels du programme
├── docs/
│   ├── GUIDE_ANIMATION.md       ← Guide d'animation du réseau associatif
│   ├── ONBOARDING_REFERENT.md   ← Kit d'intégration d'un nouveau référent
│   ├── COPIL_TEMPLATE.md        ← Modèle de COPIL mensuel prêt à l'emploi
│   └── PLAN_COMMUNICATION.md    ← Plan de communication annuel
├── src/
│   └── export.js                ← Utilitaire export CSV
└── .github/
    └── workflows/
        └── deploy.yml           ← CI/CD GitHub Pages
```

---

## ✨ Fonctionnalités du Dashboard

- **KPIs en temps réel** — taux de participation, heures cumulées, missions par statut
- **Vue Kanban** — missions À pourvoir / En cours / Réalisées, filtrables par région et thématique
- **Suivi associations** — satisfaction, missions actives, besoins identifiés
- **Réseau référents** — statut, BU, dernière interaction
- **Graphiques** — progression mensuelle sur 12 mois, répartition par thématique ESS
- **Export CSV** — toutes les données exportables en un clic

---

## 🚀 Lancer en local

```bash
git clone https://github.com/amineoualla/action-solidaire.git
cd action-solidaire
open index.html        # ou : npx serve .
```

Aucune dépendance npm requise. Le dashboard fonctionne directement dans le navigateur.

---

## 🛠️ Stack technique

| Couche | Choix |
|---|---|
| Frontend | HTML5 / CSS3 / JavaScript vanilla |
| Visualisation | Chart.js 4.x (CDN) |
| Données | JSON statique |
| CI/CD | GitHub Actions → GitHub Pages |
| Compatibilité | Office 365, Teams, SharePoint-ready |

---

## 👤 Auteur

**Amine OUALLA** — Master 2 Gestion & Management, Institut Mines Télécom Paris  
📧 amineoualla69@gmail.com · 📱 +33 7 51 17 89 61

> *Ce projet illustre ma capacité à concevoir des outils de pilotage opérationnels, à structurer une démarche chef de projet, et à maîtriser l'écosystème M365 dans un contexte d'engagement solidaire ESS.*
