# 🛡️ ISO/IEC 27001:2022 — Formation Interactive v2.0

> Application web autonome, zéro dépendance, prête pour GitHub Pages.

[![Licence: CC BY-NC-SA 4.0](https://img.shields.io/badge/Licence-CC%20BY--NC--SA%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Version](https://img.shields.io/badge/Version-2.0-navy.svg)]()
[![HTML](https://img.shields.io/badge/Fichier-Single%20HTML-orange.svg)]()
[![ISO 27001](https://img.shields.io/badge/ISO%2FIEC-27001%3A2022-teal.svg)]()

## 🚀 Démarrage rapide

### Option 1 — Ouvrir directement
Double-cliquez sur `ISO27001_Formation_V2.html` → s'ouvre dans n'importe quel navigateur moderne.

### Option 2 — GitHub Pages
```
1. Forker ce dépôt
2. Settings → Pages → Branch: main → Save
3. Renommer le fichier HTML en index.html
4. Accès : https://[username].github.io/[repo]/
```

### 🔐 Identifiants d'accès
| Champ | Valeur |
|-------|--------|
| Email | votre@email.com *(n'importe quelle adresse valide)* |
| Mot de passe | `ISO2024!` |

---

## 📚 Contenu pédagogique

### 6 modules progressifs

| Module | Titre | Clauses | Schéma |
|--------|-------|---------|--------|
| 🏛️ M1 | Fondamentaux & Contexte | Clause 4 | Cycle PDCA cliquable |
| 📋 M2 | Leadership, Planification & Support | Clauses 5, 6, 7 | Flux risques |
| ⚖️ M3 | Évaluation & Traitement des risques | Clauses 6.1, 8 | Matrice 5×5 interactive |
| 🛡️ M4 | Contrôles de l'Annexe A | Annexe A | 14 thèmes cliquables |
| 🔍 M5 | Opérations, Performance & Audit | Clauses 8, 9 | Cycle audit 6 étapes |
| 🏆 M6 | Amélioration continue & Certification | Clause 10 | Timeline certification |

### Volume pédagogique total
| Élément | Quantité |
|---------|----------|
| Questions de quiz | 60 (10 par module) |
| Flashcards | 60 (10 par module) |
| Fiches concepts | 36 (6 par module) |
| Termes de glossaire | 24 |
| Schémas interactifs | 6 |

---

## 🎓 Niveaux adaptatifs

| | 🌱 Débutant | 📘 Intermédiaire | 🔬 Avancé | 🏆 Expert |
|---|---|---|---|---|
| Timer quiz | ✗ | ✓ | ✓ | ✓ |
| Contenu avancé | ✗ | ✓ | ✓ | ✓ |
| Contenu expert | ✗ | ✗ | ✗ | ✓ |
| Déblocage progressif (≥70%) | ✗ | ✗ | ✓ | ✓ |

---

## ⚡ Fonctionnalités

| Feature | Description |
|---------|-------------|
| 🧪 Examen blanc | 30 questions · 60 min · seuil 65% |
| ⚡ Révision rapide | Sélection modules + 10 questions ciblées |
| 🔍 Recherche globale | `Ctrl+K` — modules, quiz, glossaire |
| 📊 Export CSV | Compatible Excel FR (UTF-8 BOM, sep `;`) |
| 📋 Export JSON | Structure complète pour API/backend |
| 🏅 Certificat PNG | Canvas API 1200×800 |
| 🔒 Filigrane | `© Wissem ZEDDINI` — désactivation par mot de passe |
| ⏱️ Timer intelligent | Pause si onglet inactif (Page Visibility API) |

---

## 🏆 5 Badges

| Badge | Condition |
|-------|-----------|
| 🏛️ Fondateur | Module 1 complété |
| 📋 Planificateur | Module 2 complété |
| ⚡ Expert Risques | Score ≥80% au quiz M3 |
| 🔍 Auditeur | Module 5 complété |
| 🏆 Certifié | Tous modules + moyenne ≥70% |

---

## 🛠️ Architecture

```
ISO27001_Formation_V2.html  (~1 820 lignes)
├── <style>   CSS intégré — design system complet (dark mode, niveaux)
└── <script>  JavaScript vanilla ES6+ — 4 blocs
    ├── BLOCK 1 : CONFIG · DATA (MD/QS/GL/BDG) · STATE · AUTH · LEVELS · NAV
    ├── BLOCK 2 : MODULES · QUIZ · FLASHCARDS · DIAGRAMS
    ├── BLOCK 3 : DASHBOARD · GLOSSARY · EXAM · REVISION · SEARCH
    └── BLOCK 4 : EXPORT · CERTIFICATE · SOUND · PROTECTION · INIT
```

### Config centralisée
```javascript
const CFG = {
  PASS    : 'ISO2024!',       // Mot de passe accès
  WM_PASS : 'WZEDDINI2025!',  // Mot de passe filigrane
  AUTHOR  : 'Wissem ZEDDINI',
  SEP     : ';',              // Séparateur CSV Excel FR
  IDLE_MS : 5 * 60 * 1000,   // Pause timer si inactif 5 min
  // TODO V3: backend: { enabled:false, endpoint:'', sheetsWebhook:'' }
};
```

---

## 🗺️ Roadmap V3

| Priorité | Feature |
|----------|---------|
| 🔴 Court terme | PWA offline (Service Worker) |
| 🔴 Court terme | Export PDF certificat (jsPDF) |
| 🟡 Moyen terme | Google Sheets sync (Apps Script webhook) |
| 🟡 Moyen terme | Tableau de bord formateur multi-apprenants |
| 🟢 Long terme | SCORM 1.2 / xAPI (Moodle, 360Learning) |
| 🟢 Long terme | Banque 200+ questions (algorithme Leitner) |
| 🟢 Long terme | Version multilingue EN/AR |

---

## 📁 Structure du dépôt

```
.
├── ISO27001_Formation_V2.html   ← Application complète
├── README.md                    ← Ce fichier
└── LICENSE                      ← CC BY-NC-SA 4.0
```

---

## 📜 Licence

**Creative Commons Attribution — NonCommercial — ShareAlike 4.0 International**

© 2026 Wissem ZEDDINI  
Usage pédagogique personnel uniquement — Usage commercial interdit sans autorisation écrite.

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## 🙏 Références normatives

- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)
- [ISO/IEC 27002:2022](https://www.iso.org/standard/75652)
- [ANSSI — EBIOS Risk Manager](https://www.ssi.gouv.fr/guide/ebios-risk-manager-la-methode/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

---

<div align="center">
  <strong>ISO/IEC 27001:2022 Training Platform v2.0</strong><br>
  Fait avec ❤️ pour la communauté francophone de la cybersécurité<br>
  <sub>© 2025 Wissem ZEDDINI — CC BY-NC-SA 4.0</sub>
</div>
