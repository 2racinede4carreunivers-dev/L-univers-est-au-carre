# 🧠 Carte mentale — *L'univers est au carré*

> *Empreinte structurelle et conceptuelle de l'esprit d'un analogiste.*  
> *Philippe Thomas Savard — Lévis, Chaudière-Appalaches, Canada*

---

## Introduction

Ce document est une **carte mentale vivante** du dépôt *L'univers est au carré*.  
Il n'est pas seulement un index ou une table des matières : il cherche à représenter la **structure de pensée** qui relie les travaux entre eux — la façon dont un analogiste autodidacte tisse les mathématiques, la géométrie des nombres premiers, la mécanique discrète et la philosophie du langage.

La **téléosémantique** est ici la clé de voûte : chaque fichier, chaque dossier, chaque connexion est à la fois **contenu** et **forme** — les deux ensemble transmettant une carte de l'esprit qui les a conçus.

---

## 🌐 Schéma neuronal du dépôt

```
                        ┌─────────────────────────────────┐
                        │   TÉLÉOSÉMANTIQUE ANALOGISTE    │
                        │  (philosophie / langage formel) │
                        └────────────────┬────────────────┘
                                         │
                        ┌────────────────▼────────────────┐
                        │   POSTULAT DE L'UNIVERS CARRÉ   │
                        │    (fondation géométrique)      │
                        └──┬──────────────────────────┬───┘
                           │                          │
          ┌────────────────▼──────┐      ┌────────────▼─────────────┐
          │  MÉTHODE SPECTRALE   │      │   ESPACE DE PHILIPPOT    │
          │     (Savard)         │      │   (spirale de Théodore)  │
          │  rapports 1/2·1/3·1/4│      │   pyramide & cotes       │
          └──────────┬───────────┘      └──────────┬───────────────┘
                     │                             │
          ┌──────────▼───────────────────────────▼──┐
          │         MÉCANIQUE DU CHAOS DISCRET       │
          │         (harmoniques discrètes)          │
          └──────────────────┬───────────────────────┘
                             │
                    ┌────────▼────────┐
                    │  PREUVES HOL   │
                    │  (Isabelle/HOL)│
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │  DOCUMENTS PDF  │
                    │    (LaTeX)      │
                    └─────────────────┘
```

---

## 📁 Nœuds du réseau — Fichiers et leur rôle conceptuel

### 🔵 Nœud central : Philosophie et langage

| Fichier | Rôle dans le réseau |
|---|---|
| `src/tex/teleosemantique_philosophie_esprit_analogiste.tex` | **Nœud racine** — expose la vision philosophique de l'analogiste ; la grammaire vue comme mathématique ; la téléosémantique comme méthode de compréhension structurelle |
| `src/tex/teleosemantics_mind_analogist_philosophy.tex` | Traduction anglaise du nœud racine — élargit l'audience internationale |
| `src/pdf/telosemantique_analogiste_spectre_premier.pdf` | Version compilée — document de référence pour tout lecteur curieux |

> 💡 La **téléosémantique** désigne ici la capacité d'un système de signes à orienter la pensée vers une finalité — dans ce cas, la compréhension de la géométrie des nombres premiers par analogie avec la structure du langage.

---

### 🔴 Nœud fondateur : Postulat de l'univers carré

| Fichier | Rôle dans le réseau |
|---|---|
| `src/hol/postulat_carre.thy` | **Fondation formelle** — formalisation HOL du postulat fondateur |
| `src/tex/postulat_de_univers_carre.tex` | Présentation complète du postulat avec contexte mathématique et philosophique |
| `src/pdf/postulat_univers_carre.pdf` | Version compilée — point d'entrée recommandé pour un nouveau lecteur |

> 💡 Le **postulat de l'univers carré** est la proposition centrale : la structure géométrique fondamentale de l'univers numérique est carrée — les nombres premiers s'organisent selon cette géométrie.

---

### 🟡 Nœud analytique : Méthode spectrale (Méthode Savard)

| Fichier | Rôle dans le réseau |
|---|---|
| `src/hol/methode_spectral.thy` | **Cœur formel** — preuves HOL des rapports spectraux 1/2, 1/3, 1/4 ; suites SA/SB ; Digamma ; Gap spectral |
| `src/tex/geometrie_nombre_premier.tex` | Présentation LaTeX de la géométrie du spectre des nombres premiers |
| `src/tex/prime_number_geometry.tex` | Version anglaise — accessibilité internationale |
| `src/pdf/geometrie_du_spectre_premier.pdf` | Document de référence compilé |
| `src/pdf/pilosophy_geometry_of_prime_number.pdf` | Version philosophique compilée |

> 💡 La **méthode spectrale** est l'outil analytique central : elle identifie des rapports constants (1/2, 1/3, 1/4) entre les suites de nombres premiers, révélant une structure géométrique régulière dans le spectre des premiers.

**Connexions formelles clés :**
- `SA(n) = (3.25/2) × 2ⁿ − 2` — suite A
- `SB(n) = (6.5/2) × 2ⁿ − 66` — suite B
- `RsP(n1, n2) = (SA(n1) − SA(n2)) / (SB(n1) − SB(n2)) = 1/2`
- Points de résonance : 29, 31, 37, 41
- Gap spectral (Méthode Savard) : Digamma(p) − Digamma(q)

---

### 🟢 Nœud géométrique : Espace de Philippot

| Fichier | Rôle dans le réseau |
|---|---|
| `src/hol/espace_philippot.thy` | **Formalisation HOL** — spirale de Théodore, cotes de la pyramide |
| `src/hol/methode_de_philippot.thy` | Extension formelle — méthode de Philippot |
| `src/tex/espace_de_philippot.tex` | Présentation LaTeX de l'espace géométrique |

> 💡 L'**espace de Philippot** est un espace géométrique construit sur la spirale de Théodore, où les côtés d'une pyramide suivent la loi `L(n) = √(n × Lref²)`. Il fournit un cadre géométrique à la méthode spectrale.

---

### 🟠 Nœud dynamique : Mécanique du chaos discret

| Fichier | Rôle dans le réseau |
|---|---|
| `src/hol/mecanique_discret.thy` | **Formalisation HOL** — mécanique des harmoniques discrètes |
| `src/tex/mecanique_harmonique_du_chaos_discret.tex` | Présentation LaTeX |
| `src/pdf/mecanique_chaos_discret.pdf` | Document de référence compilé |

> 💡 La **mécanique du chaos discret** explore les propriétés harmoniques des sauts entre nombres premiers — le « chaos » apparent des premiers révèle des structures harmoniques discrètes.

---

## 🔗 Connexions entre les nœuds

```
Téléosémantique ──────────► Postulat de l'univers carré
      │                              │
      │                    ┌─────────┴──────────┐
      │                    │                    │
      ▼                    ▼                    ▼
 (méta-langage)     Méthode spectrale    Espace de Philippot
                          │                    │
                          └────────┬───────────┘
                                   │
                                   ▼
                        Mécanique du chaos discret
                                   │
                          ┌────────┴────────┐
                          │                 │
                          ▼                 ▼
                      Preuves HOL      Documents LaTeX
                    (vérifiables)      (lisibles)
                          │                 │
                          └────────┬────────┘
                                   │
                                   ▼
                             PDFs + Artefacts
                          (reproductibles, attestés)
```

---

## 🧬 L'esprit de l'analogiste — Empreinte structurelle

L'auteur se définit comme **analogiste** : quelqu'un qui perçoit la grammaire comme une mathématique, les structures linguistiques comme des structures formelles, et les mathématiques comme un langage.

Cette vision se retrouve dans la structure même du dépôt :

| Dimension | Manifestation dans le dépôt |
|---|---|
| **Analogie forme/fond** | Chaque fichier `.thy` a un `.tex` correspondant — la preuve formelle et le document lisible sont deux faces du même objet |
| **Bilingue (fr/en)** | Les documents clés existent en français et en anglais — l'analogiste traduit entre les langues comme entre les systèmes formels |
| **Spirale** | La structure du dépôt suit elle-même une spirale de Théodore conceptuelle — du particulier (postulat) au général (téléosémantique) |
| **Attestation** | Chaque build génère une attestation cryptographique — la reproductibilité comme valeur épistémologique |
| **Journal vivant** | Le `CHANGELOG.md` et le `JOURNAL.md` constituent une mémoire vivante du processus — la pensée en train de se faire |

---

## 📊 Inventaire complet des fichiers sources

### Preuves formelles Isabelle/HOL (5 fichiers)

| Fichier | Concepts formalisés |
|---|---|
| `methode_spectral.thy` | Suites SA/SB, rapports spectraux 1/2·1/3·1/4, Digamma, Gap spectral |
| `methode_de_philippot.thy` | Méthode de Philippot |
| `mecanique_discret.thy` | Harmoniques du chaos discret |
| `postulat_carre.thy` | Postulat fondateur |
| `espace_philippot.thy` | Spirale de Théodore, côtés de la pyramide |

### Documents LaTeX (7 fichiers)

| Fichier | Langue | Sujet |
|---|---|---|
| `postulat_de_univers_carre.tex` | FR | Postulat de l'univers carré |
| `geometrie_nombre_premier.tex` | FR | Géométrie du spectre des nombres premiers |
| `mecanique_harmonique_du_chaos_discret.tex` | FR | Mécanique harmonique du chaos discret |
| `espace_de_philippot.tex` | FR | Espace de Philippot |
| `prime_number_geometry.tex` | EN | Geometry of the prime number spectrum |
| `teleosemantique_philosophie_esprit_analogiste.tex` | FR | Téléosémantique — philosophie de l'analogiste |
| `teleosemantics_mind_analogist_philosophy.tex` | EN | Teleosemantics — mind of the analogist |

### Documents PDF compilés (5 fichiers)

| Fichier | Contenu |
|---|---|
| `postulat_univers_carre.pdf` | Postulat de l'univers carré |
| `geometrie_du_spectre_premier.pdf` | Géométrie du spectre des nombres premiers |
| `mecanique_chaos_discret.pdf` | Mécanique du chaos discret |
| `telosemantique_analogiste_spectre_premier.pdf` | Téléosémantique de l'analogiste |
| `pilosophy_geometry_of_prime_number.pdf` | Philosophy of the geometry of prime numbers |

---

## 🔄 Cycle de vie du dépôt (CI/CD)

```
Auteur modifie .thy ou .tex
          │
          ▼
    git push → main
          │
          ▼
  GitHub Actions déclenche
  build.yml
          │
    ┌─────┴──────┐
    │            │
    ▼            ▼
Isabelle      LaTeX
  build       compile
  (.thy)      (.tex → .pdf)
    │            │
    └─────┬──────┘
          │
          ▼
  Attestation SHA-256
  (reproductibilité)
          │
          ▼
  Upload artefacts
  (PDF, metadata,
   carte mentale)
          │
          ▼
  CHANGELOG mis à jour
```

---

*Ce document est généré et maintenu manuellement — il évolue avec le dépôt.*  
*Dernière révision : voir CHANGELOG.md*
