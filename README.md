# TimeTravel Agency — Webapp Interactive

Webapp pour une agence de voyage temporel fictive, créée avec IA générative.

**Membres du groupe :** Akash SENTHILKUMAR · Hugo MORAIS MARTINS · Sean CORREA · Sabry ZOUINA · Lénusan GUNARAJAH  
**Formation :** M2 Cyber  
**Rendu :** Projet pédagogique — TimeTravel Agency

---

## 🌐 Liens

- **Webapp en ligne :** https://project-1v7u3.vercel.app
- **Repository GitHub :** https://github.com/SHODELACAILLE/timetravel-agency

---

## 🛠️ Stack Technique

- HTML5 / CSS3 / JavaScript vanilla (single-page app)
- Google Fonts : Cormorant Garamond + Outfit
- API Mistral AI — modèle `mistral-small-latest`
- Hébergement : Vercel (déploiement continu via GitHub)

---

## ✨ Features implémentées

### Phase 1 — Architecture & UI
- Hero animé avec fond étoilé et parallax au scroll
- Navigation fixe qui se solidifie au scroll
- Section "L'Agence" avec statistiques animées
- Galerie des 3 destinations avec cards cliquables et panneaux de détail dépliables
- Formulaire de réservation avec validation et confirmation
- Design responsive (mobile + desktop)

### Phase 2 — Animations (Exercice 2.3)
- Apparition en cascade des cards destinations au scroll
- Parallax sur le hero (étoiles + fond)
- Effet shimmer sur les boutons au hover
- Micro-interactions : cards, inputs, suggestions chat
- Animations de messages (scaleIn avec rebond)
- Underline animé sur les liens de navigation

### Phase 3 — Intelligence Artificielle
- **Agent conversationnel "Chronos"** — intégration API Mistral AI (mistral-small-latest)
- Mémoire de conversation (historique des messages)
- Personnalité définie : conseiller en voyages temporels de luxe
- Connaissance des 3 destinations, prix et inclusions
- **Quiz de recommandation personnalisée** (Exercice 3.2 optionnel) — 3 questions → destination idéale

---

## 🗺️ Destinations

| Destination | Époque | Durée | Prix |
|-------------|--------|-------|------|
| Paris — Belle Époque | 1889 | 5 jours | dès 12 400 € |
| Crétacé supérieur | −70 000 000 ans | 3 jours | dès 28 900 € |
| Florence — Renaissance | 1504 | 7 jours | dès 18 200 € |

---

## 🤖 IA Utilisées

| Usage | Outil |
|-------|-------|
| Génération du code webapp | Claude Sonnet 4.5 (claude.ai) |
| Agent chatbot conversationnel | Mistral AI API — mistral-small-latest |
| Visuels hero (3 images) | Google Gemini Image Generation |
| Recherche historique (Ex. 1.1) | Claude claude.ai |
| Voix-off | ElevenLabs |
| Musique d'ambiance | Suno AI |
| Vidéos image-to-video | Runway Gen-4 / Kling |
| Prompts image & vidéo | Claude claude.ai |

---

## 📁 Structure du projet

```
timetravel-agency/
├── index.html     # Webapp complète (single-page application)
└── README.md      # Documentation technique
```

---

## 🚀 Installation locale

Aucune installation requise. Ouvrir `index.html` directement dans un navigateur.

> ⚠️ Le chatbot IA nécessite une connexion internet pour appeler l'API Mistral.

---

## 📄 Licence

Projet pédagogique — M2 Cyber — Usage non commercial
