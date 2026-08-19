# Portail membres — Démo interactive

Démonstration interactive du portail membres du Regroupement des éditeurs franco-canadiens (REFC), développée dans le cadre d'un stage en coordination et communications.

> ⚠️ **DÉMONSTRATION UNIQUEMENT** — Toutes les données affichées sont entièrement fictives. Ce projet ne contient aucune donnée réelle de la REFC ou de ses maisons membres.

---

## 🔗 Lien de démonstration

[https://fallouinfo03.github.io/refc-portail-membres/](https://fallouinfo03.github.io/refc-portail-membres/)

---

## 🎯 Objectif du projet

Visualiser et valider le fonctionnement du futur portail membres de la REFC avant de soumettre le cahier des charges au prestataire de développement. Ce prototype permet de :

- Tester les parcours utilisateurs (admin et membre)
- Valider les flux de travail documentés
- Identifier les améliorations avant le développement réel
- Servir de référence visuelle pour le prestataire (Coloc, Gatineau)

---

## 📁 Structure du projet
refc-portail-membres/
├── index.html ← Page de connexion
├── assets/
│ ├── logo-refc.png ← Logo REFC (fond transparent)
│ └── logo-refc-blanc.png ← Logo REFC (version blanche topbar)
├── admin/ ← Pages vue Administrateur REFC
│ ├── tableau-de-bord.html
│ ├── couts-partages.html
│ ├── salons.html
│ ├── bulletins.html
│ └── ingram.html
├── membre/ ← Pages vue Maison membre
│ ├── tableau-de-bord.html
│ ├── couts-partages.html
│ ├── salons.html
│ ├── bulletins.html
│ └── ingram.html
└── README.md


---


---

## 🔐 Comptes de démonstration

| Rôle | Identifiant | Mot de passe |
|------|-------------|--------------|
| Admin REFC (Fadel) | `admin` | `refc2026` |
| Membre — Prise de Parole | `prisedeparole` | `demo2026` |
| Membre — David | `david` | `demo2026` |

> Ces comptes sont fictifs et n'ont aucun lien avec les systèmes réels de la REFC.

---

## 📋 Sections couvertes

| Section | Admin | Membre | Statut |
|---------|-------|--------|--------|
| Tableau de bord | ✅ | ✅ | Fait |
| Services à coûts partagés | 🔄 | 🔄 | En cours |
| Salons | 🔄 | 🔄 | En cours |
| Bulletins membres | ⏳ | ⏳ | À faire |
| Ingram | ⏳ | ⏳ | À faire |

---

## 🛠️ Technologies

- HTML5 / CSS3 / JavaScript vanilla (aucun framework)
- Déployé sur GitHub Pages (HTTPS automatique)
- Aucune base de données — données fictives en dur dans le code

---

## 👥 Développé par

- **SFM** — Stagiaire en coordination et communications, REFC
- **Bachir** — Développeur

---

## 📌 Contexte

Ce projet s'inscrit dans une démarche de digitalisation des processus internes de la REFC, notamment :
- La gestion des services à coûts partagés entre la REFC et ses 15 maisons membres
- La coordination des participations aux salons du livre
- Le suivi des distributions via Ingram (USA/Canada et Europe)

Le cahier des charges complet sera soumis à **Coloc** (coopérative web, Gatineau) pour le développement du vrai portail WordPress.
