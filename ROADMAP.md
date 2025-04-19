# 🗺️ OMNI – ROADMAP

Ce document suit l’évolution planifiée du projet Omniscience-AI (OMNI).  
Il est synchronisé avec le tableau GitHub Project `📋 OMNI – Roadmap & Avancement`.

---

## 🔁 Suivi visuel (tableau rapide)

| ✅ Statut      | 🧠 Tâche                                                                 |
|---------------|--------------------------------------------------------------------------|
| 🔜 À faire     | Ajouter CortexAgent (agent superviseur central)                         |
| 🔜 À faire     | Finaliser Gatekeeper + Watchdog                                         |
| 🔜 À faire     | Implémenter routines matin / soir / hebdo                               |
| 🔜 À faire     | Dashboard visuel (Streamlit ou React)                                   |
| 🟡 En cours    | Intégration multi-agents avec CrewAI                                    |
| 🟡 En cours    | Système de personnalité persistante (`identity_profile.yaml`)           |
| 🟡 En cours    | Test du déploiement sur DigitalOcean                                    |
| ✅ Terminé     | Fichier `REPRISE_OMNI_PROMPT.md`                                         |
| ✅ Terminé     | Structure de projet + Docker Compose complet                            |
| ✅ Terminé     | LLM Dolphin LLaMA 3 8B + Ollama                                          |
| ✅ Terminé     | Scripts `install_omni.sh` et `start_omni.sh`                            |
| ✅ Terminé     | `README.md`, `ROADMAP.md`, `CHANGELOG.md`, `CONTRIBUTING.md`            |

---

## 🔜 À faire (liste détaillée)

- [ ] Ajouter CortexAgent (agent superviseur central)
- [ ] Finaliser le Gatekeeper (authentification de démarrage)
- [ ] Implémenter le Watchdog (surveillance de dérives/erreurs)
- [ ] Créer le tableau de bord global (Streamlit ou React)
- [ ] Intégrer le mode vocal + micro écoute local
- [ ] Ajouter un plugin `calendar_agent`
- [ ] Créer les routines IA (matin / soir / hebdo)
- [ ] Implémenter l'auto-training via Agent SelfTrainer
- [ ] Automatiser les mises à jour (`omni update`)
- [ ] Ajouter un mode "Eco" (basse consommation ressources)

---

## ⚙️ En cours

- [ ] Intégration multi-agents avec CrewAI
- [ ] Système d'identité persistante (`identity_profile.yaml`)
- [ ] Tests mémoire hybride avec Qdrant + PostgreSQL
- [ ] Déploiement DigitalOcean à tester (budget < 100€/mois)

---

## ✅ Terminé

- [x] Structure de projet GitHub OK
- [x] README.md pro avec badges
- [x] CHANGELOG.md initial
- [x] Première release officielle `v0.1.0-alpha`
- [x] Scripts `install_omni.sh` et `start_omni.sh`
- [x] Docker Compose complet (LLM + Qdrant + PostgreSQL + UI)
- [x] Fichier de prompt de reprise `REPRISE_OMNI_PROMPT.md`
- [x] Badges de version, commit, licence dans README

---

## 🧠 Idées / Vision long terme

- Ajouter gestion multilingue
- IA secondaire (tâches parallèles)
- Synchronisation iPhone / iPad
- Interface mobile PWA
- Mode “famille / travail / nuit” dynamique
- Surveillance ressources système en temps réel
- Plugin ChatGPT / Claude / Gemini fallback auto

---