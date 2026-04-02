# L'univers est au carré

> *Un dépôt mathématique, formel et philosophique — par Philippe Thomas Savard, analogiste.*

[![Build Isabelle + LaTeX](https://github.com/2racinede4carreunivers-dev/L-univers-est-au-carre/actions/workflows/build.yml/badge.svg)](https://github.com/2racinede4carreunivers-dev/L-univers-est-au-carre/actions/workflows/build.yml)
[![Licence Apache 2.0](https://img.shields.io/badge/licence-Apache%202.0-blue.svg)](LICENSE)

---

## 🧠 À propos du projet

Ce dépôt est un espace de travail mathématique, formel et philosophique dédié à l'exploration de la **géométrie du spectre des nombres premiers**, du **postulat de l'univers carré** et de la **téléosémantique de l'esprit d'un analogiste**.

Il a une double vocation :

1. **Pédagogique et informationnel** — permettre à tout lecteur ou contributeur curieux de comprendre les concepts présentés, de les reproduire, de les modifier ou de les redistribuer selon les termes de la licence **Apache 2.0**.
2. **Personnel et exploratoire** — constituer une *carte mentale vivante* de l'esprit de l'auteur, une empreinte structurelle et conceptuelle de la façon dont un analogiste autodidacte appréhende les mathématiques, la géométrie des nombres premiers et la philosophie du langage formel.

> La téléosémantique et l'esprit de l'analogiste constituent la vision structurelle du dépôt : l'information transmise **et** la forme qu'elle prend cherchent ensemble à générer une représentation mentale du spécialiste qui les a conçues.

---

## 🗂️ Structure du dépôt

```
L-univers-est-au-carre/
│
├── src/
│   ├── hol/                  ← Preuves formelles Isabelle/HOL
│   │   ├── ROOT                 Session : Univers_Au_Carre
│   │   ├── methode_spectral.thy     Géométrie du spectre — rapports 1/2, 1/3, 1/4
│   │   ├── methode_de_philippot.thy Méthode de Philippot
│   │   ├── mecanique_discret.thy    Mécanique du chaos discret
│   │   ├── postulat_carre.thy       Postulat de l'univers carré
│   │   └── espace_philippot.thy     Espace de Philippot / spirale de Théodore
│   │
│   ├── tex/                  ← Sources LaTeX
│   │   ├── postulat_de_univers_carre.tex
│   │   ├── geometrie_nombre_premier.tex
│   │   ├── mecanique_harmonique_du_chaos_discret.tex
│   │   ├── espace_de_philippot.tex
│   │   ├── prime_number_geometry.tex              (en)
│   │   ├── teleosemantique_philosophie_esprit_analogiste.tex
│   │   └── teleosemantics_mind_analogist_philosophy.tex (en)
│   │
│   └── pdf/                  ← Documents PDF compilés
│       ├── postulat_univers_carre.pdf
│       ├── geometrie_du_spectre_premier.pdf
│       ├── mecanique_chaos_discret.pdf
│       ├── telosemantique_analogiste_spectre_premier.pdf
│       └── pilosophy_geometry_of_prime_number.pdf
│
├── assets/
│   └── images/               ← Figures et diagrammes
│
├── docs/
│   └── guides/               ← Guides pour contributeurs et utilisateurs
│       ├── guide_contribution.md
│       ├── guide_HOL.md
│       ├── guide_compilation.md
│       ├── guide_IA.md
│       └── guide_securite.md
│
├── scripts/                  ← Scripts utilitaires (build, versioning, journal)
├── .github/workflows/        ← CI/CD GitHub Actions
├── CARTE_MENTALE.md          ← Carte mentale / schéma neuronal du dépôt
├── CHANGELOG.md              ← Historique des modifications
└── README.md                 ← Ce fichier
```

---

## 📚 Concepts clés

| Concept | Fichiers | Description |
|---|---|---|
| **Postulat de l'univers carré** | `postulat_carre.thy`, `postulat_de_univers_carre.tex` | Fondation géométrique — l'univers comme structure carrée |
| **Méthode spectrale (Savard)** | `methode_spectral.thy`, `geometrie_nombre_premier.tex` | Rapports spectraux 1/2, 1/3, 1/4 sur les nombres premiers |
| **Méthode de Philippot** | `methode_de_philippot.thy`, `espace_de_philippot.tex` | Espace de Philippot, spirale de Théodore |
| **Mécanique du chaos discret** | `mecanique_discret.thy`, `mecanique_harmonique_du_chaos_discret.tex` | Harmoniques discrètes du chaos |
| **Téléosémantique analogiste** | `teleosemantique_philosophie_esprit_analogiste.tex` | Philosophie — la grammaire comme mathématique |

---

## 🔧 Compilation et reproduction

### Prérequis

- **Isabelle 2024** — [isabelle.in.tum.de](https://isabelle.in.tum.de/)
- **TeX Live** (avec `texlive-lang-french`, `texlive-latex-extra`)
- **Python 3** + `pygments` (pour la coloration syntaxique dans LaTeX)

### Compiler les preuves Isabelle

```bash
isabelle build -v -d src/hol Univers_Au_Carre
```

### Compiler les documents LaTeX

```bash
cd src/tex
for f in *.tex; do pdflatex -shell-escape -interaction=nonstopmode "$f"; done
```

### Via GitHub Actions

Le workflow `.github/workflows/build.yml` automatise l'ensemble de la compilation et génère les PDF et artefacts d'attestation à chaque `push` sur `main`.

---

## 🤝 Contribution

Voir [`docs/guides/guide_contribution.md`](docs/guides/guide_contribution.md) pour les détails complets.

Toute contribution est bienvenue — correction, ajout de preuves, traduction, amélioration des documents LaTeX — dans le respect de la licence Apache 2.0.

---

## 🗺️ Carte mentale

La [`CARTE_MENTALE.md`](CARTE_MENTALE.md) présente une représentation graphique et conceptuelle des connexions entre les travaux du dépôt, conçue comme une empreinte de l'esprit de l'auteur.

---

## 📄 Licence

Ce dépôt est distribué sous licence **Apache 2.0**.  
Voir le fichier [`LICENSE`](LICENSE) pour les termes complets.