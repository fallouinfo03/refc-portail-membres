# Portail membres — Démo interactive

Prototype interactif du portail membres du **Regroupement des éditeurs franco-canadiens (REFC)**, développé dans le cadre d'un stage en administration, promotion et communication.

> ⚠️ **DÉMONSTRATION UNIQUEMENT** — Toutes les données affichées sont entièrement fictives. Ce projet ne contient aucune donnée réelle de la REFC ou de ses maisons membres.

---

## Lien de démonstration

[https://fallouinfo03.github.io/refc-portail-membres/](https://fallouinfo03.github.io/refc-portail-membres/)

---

## Objectif du projet

Visualiser et valider le fonctionnement du futur portail membres de la REFC avant de soumettre le cahier des charges à un prestataire de développement. Ce prototype permet de :

- Tester les parcours utilisateurs (vue admin et vue membre)
- Valider les flux de travail internes de la REFC
- Identifier les améliorations avant le développement réel
- Servir de référence visuelle et fonctionnelle pour le développeur

---

## Structure du projet

```
refc-portail-membres/
├── index.html                        ← Page de connexion
├── assets/
│   └── REFC_Logo_acelf.png           ← Logo REFC (fond transparent)
├── admin/                            ← Vue Administrateur REFC
│   ├── tableau-de-bord.html
│   ├── couts-partages.html
│   ├── salons.html
│   ├── evenements.html
│   ├── bulletins.html
│   ├── rapports.html
│   ├── calendrier.html
│   ├── planification.html
│   ├── prix-champlain.html
│   ├── ingram.html                   ← À compléter
│   └── assistance.html
├── membre/                           ← Vue Maison membre
│   ├── tableau-de-bord.html
│   ├── couts-partages.html
│   ├── salons.html
│   ├── evenements.html
│   ├── bulletins.html
│   ├── rapports.html
│   ├── calendrier.html
│   ├── ingram.html                   ← À compléter
│   └── assistance.html
└── README.md
```

---

## Comptes de démonstration

| Rôle | Identifiant | Mot de passe |
|------|-------------|--------------|
| Admin REFC | `admin` | `refc2026` |
| Membre — Prise de Parole | `prisedeparole` | `demo2026` |

> Ces comptes sont fictifs et n'ont aucun lien avec les systèmes réels de la REFC.

---

## Modules couverts

| Module | Admin | Membre | Statut |
|--------|-------|--------|--------|
| Tableau de bord | ✅ | ✅ | Terminé |
| Coûts partagés | ✅ | ✅ | Terminé |
| Salons du livre | ✅ | ✅ | Terminé |
| Événements littéraires | ✅ | ✅ | Terminé |
| Bulletins membres | ✅ | ✅ | Terminé |
| Rapports de ventes | ✅ | ✅ | Terminé |
| Calendrier & Gouvernance | ✅ | ✅ | Terminé |
| Réalisations et performances | ✅ | — | Terminé |
| Prix Champlain | ✅ | — | Terminé |
| Ingram | ⏳ | ⏳ | À compléter |
| Assistance | ✅ | ✅ | Terminé |

---

## Fonctionnalités clés

**Vue admin**
- Tableau de bord avec alertes prioritaires, KPIs, tâches assignées et mini-calendrier
- Gestion complète des salons du livre — confirmations, commandes, factures, documents
- Approbation des factures à coûts partagés
- Suivi des événements littéraires soumis par les membres
- Calendrier de gouvernance — organes BD, AGA, ASA, CG, CP, CProg avec documents officiels (OdJ, PV, Programmation)
- Rapports de ventes — import Square et Ingram avec calcul automatique des commissions
- Prix Champlain — gestion du jury et du calendrier
- Réalisations et performances — planification stratégique annuelle

**Vue membre**
- Tableau de bord personnalisé par maison
- Confirmation de participation aux salons + soumission des commandes de livres et auteurices
- Suivi de sa propre facturation et refacturation
- Consultation des bulletins et comptes rendus
- Accès en lecture seule au calendrier de gouvernance avec téléchargement des documents

---

## Technologies

- HTML5 / CSS3 / JavaScript vanilla — aucun framework
- Déployé sur GitHub Pages (HTTPS automatique)
- Aucune base de données — données fictives intégrées dans le code

---

## Contexte

Ce prototype s'inscrit dans une démarche de digitalisation des processus internes de la REFC, organisme qui regroupe 15 maisons d'édition franco-canadiennes. Les besoins identifiés incluent :

- La gestion des services à coûts partagés entre la REFC et ses membres
- La coordination des participations aux salons, congrès et festivals du livre
- Le suivi des distributions via Ingram (Canada, USA, Europe)
- L'automatisation des processus répétitifs avec Microsoft Power Automate
- La centralisation des données dans Microsoft SharePoint

Une fois ce prototype validé par l'assemblée des membres, un cahier des charges sera rédigé à partir de la version approuvée et soumis à un prestataire de développement pour la construction de la version finale avec backend, authentification Microsoft 365 et connexion aux outils de la REFC.

---

## Développé par

**Serigne Fallou Mbacke** — Data scientist junior;
Stagiaire en administration, promotion et communication  
Regroupement des éditeurs franco-canadiens (REFC), Ottawa  
Stage 2025–2026
