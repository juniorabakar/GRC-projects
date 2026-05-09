
![banner](https://raw.githubusercontent.com/juniorabakar/GRC-Projects/main/assets/smsi_banner.svg)

<div align="center">

[![Statut](https://img.shields.io/badge/Statut-EN_COURS-e8a030?style=flat-square)]()

</div>

---

## Contexte

**MedSecure SAS** est une startup française de 45 employés développant une plateforme SaaS de gestion de dossiers patients pour les cliniques privées. Implantée à Paris et Lyon avec une partie des équipes en full-remote, l'entreprise héberge des **données de santé à caractère personnel** sur infrastructure cloud AWS.

Suite à un appel d'offres d'un groupement hospitalier public représentant un contrat de **2M€**, MedSecure se voit imposer une double exigence :

```
Exigence 1 — Certification ISO 27001:2022
Exigence 2 — Conformité HDS (Hébergeur de Données de Santé)
Délai       — 6 mois avant signature du contrat
```

**Ma mission :** concevoir et documenter le SMSI complet, prêt pour l'audit de Stage 1.

---

## Périmètre du SMSI

```
┌──────────────────────────────────────────────────────────────┐
│  PÉRIMÈTRE ISO 27001 — MedSecure SAS                         │
│                                                              │
│  Systèmes couverts                                           │
│  ├── Plateforme SaaS (application + API REST)                │
│  ├── Infrastructure cloud (AWS Paris — eu-west-3)            │
│  ├── Postes de travail (45 endpoints — Windows + macOS)      │
│  └── Outils internes (Slack, Jira, GitHub, Google Workspace) │
│                                                              │
│  Données traitées                                            │
│  ├── Données de santé (catégorie spéciale RGPD — Art. 9)     │
│  ├── Données d'identification patients                       │
│  └── Données contractuelles clients (cliniques privées)      │
│                                                              │
│  Sites                                                       │
│  ├── Paris — Siège social (30 personnes)                     │
│  ├── Lyon — Bureau régional (8 personnes)                    │
│  └── Remote — Équipes distribuées (7 personnes)              │
└──────────────────────────────────────────────────────────────┘
```

## Progression

| Clause | Livrable | Statut |
|--------|----------|--------|
| [**Clause 4** — Contexte](./Clause%204/) | Analyse contexte · Parties prenantes · Périmètre | `EN COURS` |
| **Clause 5** — Leadership | Politique SSI · Rôles & responsabilités | `À FAIRE` |
| **Clause 6** — Planification | Registre des risques · PTR · SoA | `À FAIRE` |
| **Clause 7** — Support | Documentation · Communication · Sensibilisation | `À FAIRE` |
| **Clause 8** — Fonctionnement | Politiques opérationnelles · Contrôles Annex A | `À FAIRE` |
| **Clause 9** — Évaluation | Programme d'audit interne · Revue de direction | `À FAIRE` |
| **Clause 10** — Amélioration | Non-conformités · Actions correctives | `À FAIRE` |

---

## Méthodologie

```
  Analyse du contexte organisationnel (Clause 4)
             ↓
  Identification des parties prenantes & exigences
             ↓
  Définition du périmètre SMSI
             ↓
  Évaluation des risques (vraisemblance × impact)
             ↓
  Sélection des contrôles Annex A
             ↓
  Statement of Applicability (SoA)
             ↓
  Rédaction des politiques de sécurité
             ↓
  Audit interne — constats & non-conformités
```

---

## Spécificités du contexte HealthTech

Ce projet présente des particularités importantes par rapport à un SMSI standard :

```
RGPD Art. 9    →  Données de santé = catégorie spéciale
                  Exigences renforcées de protection & traçabilité

HDS            →  Hébergement de données de santé
                  Certification complémentaire à l'ISO 27001
                  Référentiel ANS — obligatoire pour héberger des DMP

Cloud AWS      →  Responsabilité partagée (Shared Responsibility Model)
                  Contrôles Annex A adaptés au contexte cloud-native

Remote work    →  7 collaborateurs en full-remote
                  Contrôles A.6.7 (télétravail) et A.8.1 (endpoints) renforcés
```

---

## Ressources consultées

> Ces liens aident à mieux comprendre les normes officielles. **Ce ne sont pas les sites officiels, mais des ressources que je consulte régulièrement.**

<div>

[![ISO 27001:2022](https://img.shields.io/badge/Ressource-ISO_27001:2022-005A8E?style=flat-square)](https://www.iso27001security.com/)
[![HDS](https://img.shields.io/badge/Ressource-HDS-0d6efd?style=flat-square)](https://esante.gouv.fr/produits-services/hds)
[![RGPD](https://img.shields.io/badge/Ressource-RGPD_Santé-2471A3?style=flat-square)](https://www.cnil.fr/fr/les-donnees-de-sante)


</div>
---

## Leçons apprises

> *Je compléterai cette partie lorsque je serai satisfait de mon travail et du SMSI.*

---

<div align="center">

**Junior Abakar** — Consultant GRC Cybersécurité
[LinkedIn](https://www.linkedin.com/in/junior-abakar-551150265/) · [GitHub](https://github.com/juniorabakar) · juniorabakar07@gmail.com

</div>
