# Cahier des Charges — Page de Remerciement Masterclass TapiTrade
**Version :** 1.0  
**Date :** Juin 2026  
**Client :** Dany — Fondateur de TapiTrade  
**Contact :** info@tapitrade.com

---

## 1. Contexte et Objectif

### 1.1 Présentation de TapiTrade
TapiTrade est une marque éducative spécialisée dans la démocratisation des marchés financiers. Fondée par Dany, elle accompagne salariés, entrepreneurs et investisseurs à développer leur compréhension des marchés grâce à une approche fondée sur l'analyse, la discipline et la patience. La communauté compte 90+ membres actifs sur Discord, YouTube et Facebook.

### 1.2 Objectif de la page
La page `index.html` est une **page de remerciement post-inscription** à la Masterclass TapiTrade du **Dimanche 21 Juin 2026 à 19h30**. Elle est affichée après qu'un participant ait complété son inscription via un formulaire externe (ex : Typeform, Systeme.io, etc.).

### 1.3 Objectifs secondaires
- Confirmer visuellement et émotionnellement l'inscription
- Présenter un message vidéo personnel de Dany (remerciement)
- Diriger les nouveaux inscrits vers la communauté Discord
- Donner les informations pratiques de l'événement (date, heure, format)
- Présenter le formateur pour renforcer la confiance
- Offrir un canal de contact direct (`info@tapitrade.com`)

---

## 2. Structure de la Page

La page est composée de **7 blocs** dans l'ordre suivant :

| # | Bloc | Description |
|---|------|-------------|
| 1 | Navigation (sticky) | Logo + badge de l'événement |
| 2 | Hero | Titre, sous-titre, pills d'infos, vidéo |
| 3 | Discord | Invitation à rejoindre la communauté |
| 4 | À propos de Dany | Photo + biographie du formateur |
| 5 | Infos pratiques | Carte avec date, heure, format, prix |
| 6 | Footer | Liens sociaux + disclaimer légal |
| 7 | Bouton flottant + Modal | Formulaire de contact |

---

## 3. Description Détaillée des Blocs

### 3.1 Navigation (sticky)
- **Position :** fixe en haut de page au scroll
- **Fond :** blanc (`#FFFFFF`) avec ombre légère
- **Gauche :** Logo TapiTrade (hauteur 56px) — fichier `Input-Dany/Logo/Logo-TapiTrade-600x200.jpg`
- **Droite :** Badge "Masterclass Gratuite · 21 Juin" avec point animé (pulse bleu)
- **Responsive :** le badge disparaît en dessous de 640px

### 3.2 Hero
- **Eyebrow :** `MASTERCLASS GRATUITE · 21 JUIN 2026 · 19H30` (texte bleu accent, uppercase)
- **Titre :** `Comprendre les marchés / de manière simple` (Playfair Display, 34–64px responsive)
- **Sous-titre :** `Rejoignez Dany, fondateur de TapiTrade, pour une soirée en ligne 100 % gratuite afin de « Démystifier » les marchés financiers.`
- **Pills (4 badges) :**
  - Dimanche 21 Juin 2026
  - 19h30 — ~90 min
  - En ligne · Zoom
  - 100 % gratuit
- **Vidéo :** Format portrait 9:16 (style Short/Reel), max-width 340px, centré
  - Fichier : `Input-Dany/MasterClass/Remerciement InscriptionMasterClass TapiTrade.mp4`
  - Légende : `Message de Dany — Fondateur de TapiTrade`

### 3.3 Bloc Discord
- **Label :** `COMMUNAUTÉ`
- **Titre :** `Rejoins-nous déjà sur Discord`
- **Contenu dans un carré :**
  - Icône Discord + texte : `Tu as reçu les instructions dans le mail de confirmation de ton inscription.`
  - Séparateur horizontal
  - Note : `Pense à consulter aussi dans tes Spams si tu ne trouves pas l'email.`

### 3.4 À propos de Dany
- **Label :** `VOTRE FORMATEUR`
- **Titre :** `Qui est Dany ?`
- **Photo :** `Input-Dany/Photo professionnelle/Photo.png` (cercle 100×100px, bordure bleue)
- **Nom :** Dany
- **Rôle :** `Fondateur · TapiTrade`
- **Texte biographique :** Présentation de la mission de TapiTrade, communauté 90+ membres, chaîne YouTube

### 3.5 Infos pratiques
- **Label :** `INFOS PRATIQUES`
- **Titre :** `Rendez-vous le 21 Juin`
- **Sous-titre :** `Notez la date dans votre agenda. Le lien de connexion vous sera envoyé par email après inscription.`
- **Carte avec 4 lignes :**
  - Date → Dimanche 21 Juin 2026
  - Heure → 19h30 — durée ~90 minutes
  - Format → En ligne · Zoom (lien envoyé par email)
  - Prix → 100 % gratuit — places limitées

### 3.6 Footer
- **Logo texte :** TapiTrade (Playfair Display, bleu accent)
- **Liens :**
  - YouTube : `https://youtube.com/@tapitrade2.5`
  - Facebook : `https://facebook.com/TapiTrade`
- **Disclaimer légal :** mention éducative / non-conseil en investissement

### 3.7 Bouton Flottant + Modal de Contact
- **Bouton :** fixe bas-droite, bleu, "Nous envoyer un message" + icône chat
  - Mobile : icône seule (texte masqué)
- **Modal :**
  - Fond overlay sombre avec flou
  - Fermeture : bouton ×, clic sur overlay, ou Echap
  - **Champs :**
    - Nom et Prénom *(requis)*
    - Adresse e-mail *(requis)*
    - Numéro de téléphone *(optionnel)*
    - Message *(requis, max 1000 mots avec compteur en temps réel)*
  - **Bouton :** `Envoyer →`
  - **Destination :** `mailto:info@tapitrade.com` (ouvre le client mail de l'utilisateur)

---

## 4. Charte Graphique

### 4.1 Palette de couleurs

| Variable | Valeur HEX | Usage |
|----------|-----------|-------|
| `--blue-dark` | `#0D1E30` | Fond principal de la page |
| `--accent` | `#3568C8` | Couleur d'accentuation principale (bleu vif) |
| `--accent-light` | `#6090E0` | Accentuation secondaire / dégradés |
| `--accent-pale` | `#C8D8F8` | Fonds très légers |
| `--nav-bg` | `#FFFFFF` | Fond de la navigation |
| `--white` | `#FFFFFF` | Texte principal sur fond sombre |
| `--gray-mid` | `#8A96A8` | Texte secondaire / icônes |
| `--text-dark` | `#0D1E30` | Texte sur fond clair |

### 4.2 Typographie

| Police | Poids | Usage |
|--------|-------|-------|
| **Playfair Display** | 400, 600, 700 | Titres, noms, éléments éditoriaux |
| **DM Sans** | 300, 400, 500, 600 | Corps de texte, labels, boutons |

Source : Google Fonts

### 4.3 Espacements et bordures
- Radius des cartes : 14–20px
- Radius des boutons : 8–10px
- Padding sections : 72px vertical
- Container max-width : 900px centré
- Bordures : `rgba(255,255,255,0.07)` sur fond sombre, `rgba(53,104,200,0.2)` pour accent

### 4.4 Effets visuels
- Fond de page : grille subtile + dégradé radial bleu (pseudo-élément `body::before`)
- Animations au chargement : `fadeUp` (translateY + opacity)
- Animations au scroll : classe `.reveal` via IntersectionObserver
- Hover cartes : `translateY(-3px)` + changement de bordure
- Bouton hover : `translateY(-2px)` + ombre renforcée

---

## 5. Comportements Interactifs

| Fonctionnalité | Description |
|---------------|-------------|
| Navigation sticky | La barre reste visible lors du scroll |
| Scroll reveal | Les sections apparaissent en fondu au scroll |
| Vidéo intégrée | Lecteur natif HTML5 avec contrôles, format portrait 9:16 |
| Point pulsant | Indicateur animé dans le badge nav |
| Bouton flottant | Toujours visible, ouvre le modal au clic |
| Modal contact | S'ouvre/ferme avec animation, bloque le scroll de fond |
| Compteur de mots | Temps réel, vire au rouge à l'approche de 1000 mots |
| Envoi du formulaire | Ouvre le client mail avec sujet et corps pré-remplis |

---

## 6. Fichiers et Ressources

### 6.1 Fichiers produits
| Fichier | Rôle |
|---------|------|
| `index.html` | Page principale (tout-en-un : HTML + CSS + JS) |
| `Input-Dany/MasterClass/merci-masterclass.html` | Page merci alternative (existante) |

### 6.2 Assets utilisés
| Fichier | Usage |
|---------|-------|
| `Input-Dany/Logo/Logo-TapiTrade-600x200.jpg` | Logo dans la navigation |
| `Input-Dany/Photo professionnelle/Photo.png` | Photo de Dany dans la section formateur |
| `Input-Dany/MasterClass/Remerciement InscriptionMasterClass TapiTrade.mp4` | Vidéo hero (format portrait) |

### 6.3 Dépendances externes
| Ressource | Source |
|-----------|--------|
| Google Fonts (Playfair Display + DM Sans) | `fonts.googleapis.com` |
| Icônes SVG | Inline dans le HTML (aucune dépendance externe) |

---

## 7. Contraintes Techniques

- **Type :** Page statique HTML/CSS/JS — aucun back-end, aucune base de données
- **Compatibilité :** Navigateurs modernes (Chrome, Firefox, Safari, Edge)
- **Responsive :** Optimisée mobile (breakpoint principal : 640px, modal : 480px)
- **Hébergement recommandé :** Netlify Drop (glisser-déposer le dossier → URL publique instantanée)
- **Envoi d'emails :** Via `mailto:` (ouvre le client mail de l'utilisateur). Pour un envoi direct sans client mail, intégrer un service tiers : Formspree, EmailJS ou Brevo

---

## 8. Informations de l'Événement

| Champ | Valeur |
|-------|--------|
| Nom | Masterclass TapiTrade |
| Date | Dimanche 21 Juin 2026 |
| Heure | 19h30 |
| Durée estimée | ~90 minutes |
| Format | En ligne — Zoom |
| Prix | Gratuit |
| Lien de connexion | Envoyé par email aux inscrits |

---

## 9. Évolutions Futures Identifiées

| Priorité | Évolution |
|----------|-----------|
| Haute | Remplacer `mailto:` par un envoi direct (Formspree / EmailJS) pour le formulaire de contact |
| Haute | Héberger la page sur un domaine personnalisé (ex : `masterclass.tapitrade.com`) |
| Moyenne | Ajouter un lien Discord cliquable dans le bloc communauté |
| Moyenne | Intégrer un bouton "Ajouter à Google Agenda / Apple Calendar" |
| Basse | Ajouter une section témoignages/avis de membres de la communauté |
| Basse | Tracker les visites avec Google Analytics ou Plausible |

---

## 10. Mentions Légales

> Les contenus proposés par TapiTrade ont un objectif exclusivement éducatif et informatif. Ils ne constituent pas des conseils en investissement, des recommandations d'achat ou de vente, ni une garantie de performance future. Investir comporte des risques de perte en capital.

---

*Document produit sur la base du code source `index.html` — Juin 2026*
