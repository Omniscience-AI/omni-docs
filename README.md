# 🧠 Omniscience-AI (OMNI)

![GitHub release](https://img.shields.io/github/v/release/Omniscience-AI/omniscience-ai?label=version&color=blue)
![Dernier commit](https://img.shields.io/github/last-commit/Omniscience-AI/omniscience-ai)
![Licence](https://img.shields.io/github/license/Omniscience-AI/omniscience-ai)

OMNI est une intelligence artificielle personnelle, évolutive, souveraine, installée localement ou sur le cloud.  
Elle est capable de mémoriser, apprendre, interagir avec mon environnement (Mac, web, APIs), et évoluer avec moi dans le temps.

---

## 🔭 Roadmap
📍 [Voir la feuille de route complète du projet (ROADMAP.md)](ROADMAP.md)  
📊 [Version tableau rapide et synthétique (ROADMAP_TABLE.md)](ROADMAP_TABLE.md)

---

## 🚀 Installation rapide

### Option 1 – Docker (recommandé)
```bash
docker-compose up -d
```

### Option 2 – Installation locale
```bash
bash install_omni.sh
bash start_omni.sh
```

---

## 📦 Structure du projet

```
omniscience-ai/
├── omni_core/              # Backend FastAPI (API principale d’OMNI)
├── frontend/               # Interface utilisateur (Streamlit ou React)
├── config/                 # Fichiers de configuration (tools, identity, memory, plugins)
├── install_omni.sh         # Script d'installation locale
├── start_omni.sh           # Script de démarrage
├── docker-compose.yml      # Stack Docker complète
├── REPRISE_OMNI_PROMPT.md  # Reprise rapide après reset
├── ROADMAP.md              # Suivi de l'avancement (version complète)
├── ROADMAP_TABLE.md        # Version synthétique et visuelle
├── CHANGELOG.md            # Historique des versions
└── README.md
```

---

## 🧠 Modules inclus

- ✔️ **LLM local** (Dolphin LLaMA 3 8B via Ollama)
- ✔️ Mémoire hybride (Qdrant + PostgreSQL)
- ✔️ Agents IA (CrewAI + Cortex)
- ✔️ Outils intelligents (CalcTool, DictTool…)
- ✔️ Interface CLI + Web
- ✔️ Plugins dynamiques (api_connector, plugins.yaml)
- ✔️ Sécurité (Gatekeeper, Watchdog)
- ✔️ Personnalité évolutive (`identity_profile.yaml`)

---

## 📌 Statut : `v0.1.0-alpha` – Stable pour usage local ou cloud (DigitalOcean)