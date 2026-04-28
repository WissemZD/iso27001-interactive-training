# 🛡️ ISO/IEC 27001:2022 — Formation Interactive v2.0

> **Plateforme de formation professionnelle** à la norme ISO/IEC 27001:2022 — Application web autonome, zéro dépendance, prête pour GitHub Pages.

[![Licence: CC BY-NC-SA 4.0](https://img.shields.io/badge/Licence-CC%20BY--NC--SA%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Version](https://img.shields.io/badge/Version-2.0-navy.svg)]()
[![HTML](https://img.shields.io/badge/HTML-Single%20File-orange.svg)]()
[![ISO 27001](https://img.shields.io/badge/ISO%2FIEC-27001%3A2022-teal.svg)]()

---

## 📋 Présentation

Application Single-Page (SPA) **100 % autonome** permettant à des professionnels (DSI, RSSI, auditeurs, chefs de projet SI) de se former à l'ISO/IEC 27001:2022 de manière interactive et progressive.

### ✨ Ce qui la distingue

- **Un seul fichier HTML** — aucun serveur, aucune dépendance npm, aucune installation
- **Compatible GitHub Pages** — hébergement gratuit en 30 secondes
- **Niveaux adaptatifs** — contenu et quiz ajustés selon le profil de l'apprenant
- **Progression persistante** — sauvegardée localement (localStorage)
- **Protection auteur** — filigrane sécurisé par mot de passe, protection légère du contenu

---

## 🚀 Démarrage rapide

### Option 1 — Ouvrir directement
```bash
# Télécharger le fichier
# Double-cliquer sur ISO27001_Formation_V2.html
# → S'ouvre dans n'importe quel navigateur moderne
```

### Option 2 — GitHub Pages
```bash
# 1. Forker ce dépôt
# 2. Settings → Pages → Branch: main → Save
# 3. Votre formation est en ligne à : https://[username].github.io/[repo]/
```

### Option 3 — Cloner & héberger
```bash
git clone https://github.com/WissemZD/iso27001-formation.git
cd iso27001-formation
# Ouvrir ISO27001_Formation_V2.html dans votre navigateur
```

### 🔐 Identifiants d'accès
| Champ | Valeur |
|-------|--------|
| Email | votre@email.com *(n'importe quelle adresse valide)* |
| Mot de passe | `ISO2024!` |

> **Administrateurs** : Le mot de passe est configurable dans la constante `CFG.DEFAULT_PASSWORD` en tête du script JS.

---

## 📚 Contenu pédagogique

### 6 modules progressifs

| Module | Titre | Clauses ISO | Contenu |
|--------|-------|-------------|---------|
| 🏛️ M1 | Fondamentaux & Contexte | Clause 4 | SMSI, PDCA, trilogie CIA, contexte organisationnel |
| 📋 M2 | Leadership, Planification & Support | Clauses 5, 6, 7 | Politique SI, PTR, 4 options de traitement, compétences |
| ⚖️ M3 | Évaluation & Traitement des risques | Clauses 6.1, 8 | Matrice 5×5, SoA, reproductibilité, fonctionnement opérationnel |
| 🛡️ M4 | Contrôles de l'Annexe A | Annexe A complète | 11 thèmes, 93 contrôles, 4 nouveaux contrôles 2022 |
| 🔍 M5 | Opérations, Performance & Audit | Clauses 8, 9 | KPIs, audit interne, NC majeure/mineure, revue de direction |
| 🏆 M6 | Amélioration continue & Certification | Clause 10 | 5 Pourquoi, Stade 1 & 2, cycle de certification 3 ans |

### Pour chaque module
- **📖 Résumé synthétique** avec contenu adaptatif selon le niveau
- **💡 6 fiches concepts** clés interactives
- **📊 Schéma interactif** (PDCA, flux de risques, matrice, Annexe A, audit, timeline)
- **🃏 10 flashcards** flip (recto : question / verso : réponse détaillée)
- **✏️ Quiz de 10 questions** avec feedback immédiat, badge de difficulté et timer adaptatif

### Volume pédagogique
- **60 questions de quiz** avec corrigés et explications détaillées
- **60 flashcards** thématiques
- **24 fiches concepts** (6 par module)
- **6 schémas interactifs** cliquables/survolables
- **24 termes** dans le glossaire avec recherche en temps réel

---

## 🎓 Niveaux d'apprentissage adaptatifs

| Niveau | 🌱 Débutant | 📘 Intermédiaire | 🔬 Avancé | 🏆 Expert |
|--------|-------------|------------------|-----------|-----------|
| Timer quiz | ✗ | ✓ | ✓ | ✓ |
| Contenu avancé | ✗ | ✓ | ✓ | ✓ |
| Contenu expert | ✗ | ✗ | ✗ | ✓ |
| Déblocage progressif (≥70%) | ✗ | ✗ | ✓ | ✓ |
| Difficulté des questions | Facile | Facile → Moyen | → Difficile | → Expert |

Le niveau est sélectionnable à la connexion et modifiable à tout moment via ⚙️ **Paramètres**.

---

## 🏆 Gamification

### 5 badges à débloquer
| Badge | Condition |
|-------|-----------|
| 🏛️ Fondateur | Compléter le Module 1 |
| 📋 Planificateur | Compléter le Module 2 |
| ⚡ Expert Risques | Score ≥ 80% au quiz du Module 3 |
| 🔍 Auditeur | Compléter le Module 5 |
| 🏆 Certifié | Tous les modules complétés + score moyen ≥ 70% |

---

## ⚡ Fonctionnalités avancées

### 🧪 Examen blanc
- 30 questions aléatoires couvrant les 6 modules
- Minuteur de 60 minutes avec compte à rebours
- Seuil de réussite : 65% (simulation certification)
- Résultats détaillés par module avec recommandations de révision

### ⚡ Mode révision rapide
- Sélection ciblée des modules à réviser
- Quiz de 10 questions avec feedback immédiat
- Accessible depuis n'importe quel module (sidebar)

### 🔍 Recherche globale (`Ctrl+K`)
- Recherche simultanée dans les modules, flashcards, concepts, quiz et glossaire
- Navigation directe vers le contenu trouvé

### 📊 Export de progression
- **CSV** : compatible Excel FR (UTF-8 BOM, séparateur `;`) — prêt pour archivage RH
- **JSON** : structure complète avec métadonnées — prêt pour intégration API/LMS

### 🏅 Certificat de complétion
- Généré en PNG via Canvas API
- Inclut score moyen, date d'émission, signature auteur
- Disponible après complétion des 6 modules

---

## 🔒 Sécurité & Protection auteur

### Protection du contenu (PROTECTED: CC BY-NC-SA 4.0)
- **Clic droit désactivé** avec notification discrète
- **Raccourcis d'inspection** interceptés (`Ctrl+Shift+I`, `Ctrl+U`, `F12`, `PrintScreen`)
- **Renforcement à l'impression** (filigrane amplifié)

### Filigrane auteur
- Filigrane permanent `© Wissem ZEDDINI — Formation ISO 27001:2022`
- **Désactivation protégée par mot de passe** (mot de passe auteur séparé)
- Configurable via `CFG.WM_PASSWORD` dans le code source

### Authentification légère
- Email + mot de passe requis au premier chargement
- Identifiant anonyme `anon_xxxxxxxx` généré par hash (aucune donnée envoyée)
- Session persistée en `localStorage` (aucun serveur, aucune collecte de données)

---

## ⏱️ Compteur de temps intelligent

- **Pause automatique** si l'onglet n'est pas actif (Page Visibility API)
- **Détection d'inactivité** : le timer se suspend si l'utilisateur ne montre aucune interaction pendant plus de 5 minutes
- Mesure uniquement le temps d'**apprentissage actif** réel

---

## 🛠️ Architecture technique

```
ISO27001_Formation_V2.html          ← Fichier unique autonome (~3 300 lignes)
├── <style>                         ← CSS intégré (design system complet)
│   ├── Variables CSS custom properties (light/dark mode)
│   ├── Composants : cards, buttons, badges, progress bars
│   ├── Modules : quiz, flashcards, diagrams, glossary, exam
│   └── V2 additions : auth gate, level system, watermark, export
└── <script>                        ← JavaScript vanilla ES6+ (sections commentées)
    ├── CONFIG      — CFG object centralisé
    ├── DATA        — Modules, questions, glossaire, badges
    ├── STATE       — Persistance localStorage
    ├── AUTH        — Authentification légère
    ├── LEVELS      — Système de niveaux adaptatifs
    ├── NAV         — Navigation SPA
    ├── MODULES     — Rendu dynamique des modules
    ├── QUIZ        — Moteur de quiz interactif
    ├── FLASHCARDS  — Système flip cards
    ├── DIAGRAMS    — Schémas interactifs SVG/CSS
    ├── DASHBOARD   — Tableau de bord personnalisé
    ├── GLOSSARY    — Recherche en temps réel
    ├── EXAM        — Mode examen blanc 60 min
    ├── REVISION    — Mode révision ciblée
    ├── SEARCH      — Recherche globale Ctrl+K
    ├── EXPORT      — CSV + JSON (Excel-ready)
    ├── CERTIFICATE — Canvas API → PNG
    ├── PROTECT     — Protection contenu
    ├── SOUND       — Web Audio API
    ├── SETTINGS    — Modal paramètres
    └── INIT        — Bootstrap + visibility tracking
```

### Configuration centralisée (`CFG`)
```javascript
const CFG = {
  DEFAULT_PASSWORD : 'ISO2024!',        // Mot de passe accès formation
  WM_PASSWORD      : 'WZEDDINI2025!',   // Mot de passe désactivation filigrane
  AUTHOR_NAME      : 'Wissem ZEDDINI',
  APP_VERSION      : '2.0',
  LICENSE          : 'CC BY-NC-SA 4.0',
  CSV_SEP          : ';',               // Séparateur Excel FR
  PROG_LOCK_SCORE  : 70,                // Score min déblocage progressif (%)
  LEVELS           : [ ... ]            // 4 niveaux adaptatifs
  // TODO V3: backend: { enabled:false, endpoint:'', sheetsWebhook:'' }
};
```

---

## 🗺️ Roadmap V3 (contributions bienvenues)

- [ ] **Backend leger** : endpoint REST pour synchronisation des scores
- [ ] **Google Sheets** : export automatique via Apps Script webhook
- [ ] **SCORM 1.2 / xAPI** : intégration LMS (Moodle, 360Learning)
- [ ] **Mode hors-ligne** (PWA) : Service Worker + cache manifest
- [ ] **Multilingue** : internationalisation EN/AR
- [ ] **Analytics** : tableau de bord formateur avec agrégation des scores
- [ ] **Questions supplémentaires** : banque de 200+ questions avec pondération aléatoire

---

## 📁 Structure du dépôt

```
.
├── ISO27001_Formation_V2.html      ← Application complète (fichier principal)
├── README.md                       ← Ce fichier
└── LICENSE                         ← Texte complet CC BY-NC-SA 4.0
```

---

## 📜 Licence

**Creative Commons Attribution - NonCommercial - ShareAlike 4.0 International**

```
© 2025 Wissem ZEDDINI

Vous êtes autorisé à :
✅ Partager — copier et redistribuer dans tout support ou format
✅ Adapter — remixer, transformer et construire à partir du matériel

Selon les conditions suivantes :
📌 Attribution  — Vous devez créditer l'auteur (Wissem ZEDDINI)
🚫 Non-Commercial — Usage commercial interdit sans autorisation écrite
🔄 ShareAlike — Si vous adaptez, vous devez distribuer sous la même licence

Usage pédagogique personnel uniquement.
Contact pour licence commerciale : wzeddini@formation-iso27001.tn
```

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## 👤 Auteur

**Wissem ZEDDINI**
Étudiant en Master IASRIA (Ingénierie Avancée des Systèmes Robotisés et Intelligence Artificielle)

*Formation ISO/IEC 27001:2022 — Système de Management de la Sécurité de l'Information*

---

## 🙏 Références

- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001) — Norme officielle
- [ISO/IEC 27002:2022](https://www.iso.org/standard/75652) — Guide de mise en œuvre
- [ANSSI — EBIOS Risk Manager](https://www.ssi.gouv.fr/guide/ebios-risk-manager-la-methode/)
- [CNIL — Sécurité des données personnelles](https://www.cnil.fr/fr/securite-des-donnees)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

---

<div align="center">
  <strong>ISO/IEC 27001:2022 Training Platform v2.0</strong><br>
  Fait avec ❤️ pour la communauté francophone de la cybersécurité<br>
  <sub>© 2026 Wissem ZEDDINI — CC BY-NC-SA 4.0</sub>
</div>
