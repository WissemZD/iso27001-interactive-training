# 🛡️ ISO/IEC 27001:2022 – Interactive Training Platform

Une application web **autonome, légère et pédagogique** pour maîtriser la norme ISO/IEC 27001:2022. Conçue pour les DSI, RSSI, auditeurs et chefs de projet SI, elle propose un parcours progressif avec quiz, flashcards, suivi de progression et simulateur d'examen.

> ✅ **Zéro dépendance** • 📱 **Responsive** • 💾 **Sauvegarde locale** • 🌐 **Fonctionne offline**

---

## ✨ Fonctionnalités

| Module | Contenu | Évaluation |
|--------|---------|------------|
| **M1** | Fondamentaux & Contexte organisationnel | 5 QCM + Glossaire interactif |
| **M2** | Leadership, Planification & Support | 5 QCM + Flashcards |
| **M3** | Évaluation & Traitement des risques | 5 QCM + Matrice 5×5 |
| **M4** | Contrôles de l'Annexe A (11 thèmes, 93 contrôles) | 5 QCM + Nouveautés 2022 |
| **M5** | Opérations, Performance & Audit interne | 5 QCM + Cas pratiques |
| **M6** | Amélioration continue & Certification | 5 QCM + Parcours Stade 1/2 |

- 🔄 **Progression persistante** via `localStorage` (scores, modules complétés, badges)
- 🌗 **Mode clair/sombre** natif
- 📚 **Glossaire dynamique** avec recherche en temps réel
- 🎯 **Mode révision** : relance automatique des quiz < 70%
- 📄 **Simulateur d'examen** : 30 questions chronométrées, correction détaillée

---

## 🛠️ Stack Technique
HTML5 (Sémantique) + CSS3 (Custom Properties, Flex/Grid) + JavaScript ES6+ (Vanilla)
- Aucun framework, aucune CDN, aucune dépendance externe
- Architecture modulaire : `renderQuiz()`, `saveProgress()`, `toggleTheme()`
- Optimisé pour les navigateurs modernes & mobile-first

---

## 🚀 Utilisation

1. Télécharge ou clone le repository
2. Ouvre `index.html` dans un navigateur moderne (Chrome, Firefox, Edge, Safari)
3. Commence la formation → Ta progression est sauvegardée automatiquement
4. Pour déployer en ligne : active **GitHub Pages** (voir section ci-dessous)

> 💡 **Note** : Toutes les données (scores, badges, réponses) restent sur ton appareil (`localStorage`). Aucune donnée n'est envoyée à un serveur tiers.

---

## 🌐 Déploiement Gratuit (GitHub Pages)

1. Va dans `Settings` → `Pages`
2. Sous `Source`, sélectionne `Deploy from a branch`
3. Branche : `main` (ou `master`), Dossier : `/(root)`
4. Clique sur `Save` → Ton application sera accessible à `https://[ton-username].github.io/iso27001-interactive-training/`

---

## 🗺️ Roadmap & Améliorations Futures

- [ ] Export PDF/JSON de la progression
- [ ] Audio Overviews intégrés (générés via NotebookLM)
- [ ] Support multi-langue (FR/EN/AR)
- [ ] Analytics anonymes opt-in (privacy-friendly)
- [ ] Intégration de prompts NotebookLM directement dans l'interface
- [ ] Mode collaboratif / partage de scores (optionnel)

---

## 🤝 Contribuer

Les retours d'expérience, corrections techniques ou suggestions pédagogiques sont les bienvenus :
1. `Fork` le projet
2. Crée une branche (`feature/amélioration-xyz`)
3. Commit tes modifications
4. Ouvre une `Pull Request`

Pour les suggestions de contenu normatif, merci de citer la clause ISO 27001:2022 concernée.

---

## 📄 License

- **Code** : MIT License (voir `LICENSE`)
- **Contenu pédagogique** : CC BY-NC-SA 4.0 (partage non-commercial, attribution requise)

---
## 👤 Auteur

**Wissem ZEDDINI** - RSSI/DSI en Tunisie  
Idée originale & développement assisté par IA  
(https://github.com/WissemZD)

---
## 🙏 Crédits & Remerciements

- Norme de référence : `ISO/IEC 27001:2022`
- Génération IA : Claude (Anthropic) + Prompt Engineering pédagogique
- Inspiration : Guides ANSSI, ISO 27002:2022, EBIOS RM, PECB Training Framework
- Conçu pour la communauté cybersécurité & conformité SI

> ⚠️ *Ce projet est un outil d'apprentissage. Il ne remplace pas la lecture officielle de la norme ISO/IEC 27001:2022 ni une certification accréditée.*
