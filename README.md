# 🤖 MedBot - Agent Conversationnel Intelligent (DialogFlow & NLP)

**MedBot** est un agent conversationnel conçu pour automatiser la prise de rendez-vous. Il utilise le traitement du langage naturel (NLP) pour comprendre les besoins des utilisateurs et interagir avec des outils tiers via des API.

---

## 🛠 Technologies & Intégrations
- **NLP Engine :** Google DialogFlow (Gestion des intents, des entités et du machine learning).
- **Interface Utilisateur :** Déploiement via l'API Telegram.
- **Service Cloud :** Google Calendar API pour la synchronisation des rendez-vous.
- **Workflow :** Utilisation de Webhooks pour lier les conversations aux actions réelles.

## ✨ Fonctionnalités clés
- **Compréhension du Langage Naturel :** Capacité à identifier les intentions de prise de rendez-vous, d'annulation ou de demande d'informations.
- **Extraction intelligente de données (Slot Filling) :** Capture automatique des dates, heures et types de services sans formulaire rigide.
- **Automatisation de l'Agenda :** Vérification des disponibilités et création instantanée d'événements dans le calendrier.
- **Gestion des flux :** Scénarios de réponse adaptés aux demandes de l'utilisateur (fallback, relance, confirmation).

## 🚀 Réalisation technique
1. **Entraînement du modèle :** Configuration de jeux de données d'entraînement pour optimiser le score de confiance (*Confidence Score*) de l'agent.
2. **Architecture des Intents :** Modélisation d'une structure logique permettant de maintenir le contexte sur plusieurs échanges.
3. **Interopération :** Configuration et sécurisation de la communication entre DialogFlow, Telegram et les services Google.

## 📂 Contenu du dépôt
- `README.md` : Documentation technique.
- `docs/` : Documentation complète sur la conception du bot.
- `assets/` : Captures d'écran de l'interface et du flux logique.

---
*Développé par Adam Mohamed*
