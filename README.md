# 🤖 TechBot Support 1.0

> Un assistant virtuel intelligent pour répondre aux questions courantes de support technique grâce au modèle de langage **Gemma** et à une base de connaissance interne.

---

## 🎯 Objectif du projet

Créer un chatbot intelligent qui peut répondre à des questions fréquentes de support IT (niveau 1) en combinant :
- Le **modèle de langage Gemma** (open-source de Google)
- Une **base documentaire interne** (extraits de Bookstack / GLPI)

---

## 👥 Équipe

| Membre             | Rôle dans le projet                                                |
|--------------------|---------------------------------------------------------------------|
| Coordinateur (Toi) | Planification, organisation, tests, documentation                   |
| Développeur        | Intégration Gemma, interface utilisateur, logique d’interrogation   |
| Data Analyst       | Préparation des données, structuration des cas, évaluation qualité  |
| Technicien IT      | Fourniture de cas concrets, export de la base documentaire, validation technique |

---

## 🗺️ Étapes du projet (Feuille de route)

### ✅ Phase 1 : Démarrage et organisation (Jour 1–3)
- Créer un dépôt GitHub
- Lancer un notebook Kaggle avec Gemma
- Définir une dizaine de cas d’usage fréquents en support

---

### 🔍 Phase 2 : Base de connaissance (Jour 3–6)
- Exporter les pages techniques de Bookstack / GLPI
- Nettoyer et découper les documents en blocs courts
- Préparer une structure de recherche (type RAG simple)

---

### 🧠 Phase 3 : Intégration de Gemma (Jour 5–8)
- Créer un prompt efficace utilisant le contexte extrait
- Tester des requêtes utilisateur + documents internes
- Affiner le format de réponse générée

---

### 💬 Phase 4 : Interface utilisateur (Jour 7–10)
- Créer une interface simple (Streamlit ou Gradio)
- Entrée : question de l’utilisateur
- Sortie : réponse générée par Gemma avec base de connaissance

---

### 🧪 Phase 5 : Tests et amélioration (Jour 10–13)
- Tester avec des cas réels
- Mesurer la pertinence des réponses
- Corriger, améliorer les prompts, la recherche, l’affichage

---

### 🏁 Phase 6 : Finalisation et soumission (Jour 13–14)
- Nettoyer le code
- Rédiger un README clair
- Soumettre sur Kaggle (notebook + présentation)

---

## 📦 Livrables attendus

- ✅ Un **Notebook Kaggle** avec :
  - Le code complet
  - Des cas d’utilisation testés
  - Une explication claire
- ✅ Une **interface utilisateur simple**
- ✅ Une **présentation du projet** (README ou slide)

---

## 📅 Deadline du hackathon

> À confirmer sur Kaggle :  
**[Lien vers le hackathon Google Gemma 3N](https://www.kaggle.com/competitions/google-gemma-3n-hackathon)**

Prévoir soumission **avant la date de clôture officielle** (estimée autour de mi-juillet 2025).

---

## 💡 Prochaine étape

- [ ] Valider la liste des cas d’usage
- [ ] Préparer l’extraction de Bookstack ou GLPI
- [ ] Tester un premier prompt avec Gemma sur Kaggle

---
