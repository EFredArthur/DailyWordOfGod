# DailyWordOfGod

# 📖 La Parole au Quotidien

> **Plateforme Éditoriale Spirituelle Unifiée**  
> Centralisation officielle de 10 blogs thématiques, leçons quotidiennes, études bibliques par trimestres et espace communautaire de partage et de méditation.

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com)
[![React](https://img.shields.io/badge/React-19-61dafb.svg)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178c6.svg)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.x-38b2ac.svg)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-8.x-646cff.svg)](https://vitejs.dev)
[![License](https://img.shields.io/badge/License-Apache--2.0-green.svg)](LICENSE)

---

## 📌 Présentation du Projet

**La Parole au Quotidien** est une plateforme web moderne conçue pour répondre à un défi majeur : **l'éparpillement des ressources spirituelles et bibliques**. 

Le projet rassemble en une interface épurée, apaisante et hautement accessible :
- **10 blogs thématiques unifiés** couvrant la doctrine, la santé holistique, la prophétie, la famille, la prière et la science.
- **La Leçon / Publication du Jour** mise en avant automatiquement chaque matin avec verset d'ancrage en exergue.
- **Une organisation temporelle par trimestres d'étude** (façon École du Sabbat), avec archivage historique.
- **La Bibliothèque Communautaire (Explorer les Articles)** : un espace où chacun peut consulter les articles de tous les contributeurs, filtrer par auteur/thème/trimestre, et enregistrer ses favoris.
- **Un système de commentaires avec modération pastorale bienveillante** pour préserver la paix et la qualité des échanges.
- **Un Back-office d'administration et de rédaction complet** intégrant un éditeur WYSIWYG avec coloration spirituelle des versets, sauvegarde automatique locale (toutes les 30s) et import/nettoyage de textes externes.

---

## 🎯 À quoi sert la plateforme ?

1. **Pour les Fidèles & Lecteurs du Quotidien :**
   - Nourrir leur foi dès l'aube grâce à la *Leçon du Jour*.
   - Écouter les méditations en audio grâce au synthétiseur vocal intégré.
   - Régler la taille du texte (confort de lecture A / A+ / A++).
   - Trouver facilement des réponses spirituelles grâce au moteur de recherche multicritère.
   - Enregistrer leurs leçons préférées dans l'onglet **Mes Favoris**.
   - Partager des réflexions ou témoignages via l'espace de commentaires.
   - Personnaliser leur profil lecteur (nom, nom d'utilisateur `@pseudo`, photo/couleur d'avatar).

2. **Pour les Pasteurs, Rédacteurs & Contributeurs :**
   - Rédiger et formater des enseignements riches avec mise en valeur de versets bibliques (*Or Sacré, Bleu Céleste, Pourpre Royal*).
   - Rattacher obligatoirement chaque article à un Thème et un Trimestre (avec détection automatique selon la date).
   - Importer du contenu depuis d'anciens blogs, emails ou documents Word via un nettoyeur automatique anti-XSS.
   - Mettre en avant un article comme *Publication du Jour* sur la page d'accueil en un clic.

3. **Pour les Administrateurs :**
   - Suivre les indicateurs clés en temps réel (articles publiés, brouillons, thèmes actifs, commentaires).
   - Modérer les commentaires des lecteurs (*Approuver*, *Rejeter* ou *Supprimer*).

---

## 🏛️ Les 10 Blogs & Volets Thématiques Unifiés

| # | Thématique | Blog Source | Description |
|---|------------|-------------|-------------|
| **01** | **Étude Biblique & Doctrine** | *La Parole Vivante* | Exégèse approfondie et fondements de la foi chrétienne |
| **02** | **Santé & Tempérance** | *Temple Vivant & Santé* | Lois naturelles de la santé et équilibre holistique |
| **03** | **Esprit de Prophétie** | *Lumière sur le Sentier* | Éclairages prophétiques et conseils pour les derniers jours |
| **04** | **Vie Chrétienne & Foi** | *Marcher par la Foi* | Application quotidienne des principes de l’Évangile |
| **05** | **Famille & Foyer Chrétien** | *Le Foyer Restauré* | Couple chrétien, éducation des enfants et foyer sanctifié |
| **06** | **Mission & Évangélisation** | *Aux Quatre Vents* | Proclamation de l’Évangile éternel et action sociale |
| **07** | **Jeunesse & Foi** | *Génération Relève* | Réponses aux défis de la jeunesse chrétienne contemporaine |
| **08** | **Création, Science & Foi** | *Révélation & Nature* | Harmonie entre la Genèse et la science authentique |
| **09** | **Histoire & Pionniers** | *Bornes Anciennes* | Héritage historique et leçons tirées du passé |
| **10** | **Prière & Méditation** | *L’Heure Silencieuse* | Recueillement personnel et intimité avec le Créateur |

---

## 🎨 Charte Graphique & Ergonomie

L'application respecte rigoureusement la constitution visuelle spirituelle édictée dans le cahier des charges :
- **Typographie des Grands Titres :** `Anton` (impact visuel, autorité, clarté).
- **Typographie du Corps de Texte :** `Fira Sans` (élégance, fluidité et lecture prolongée sans fatigue oculaire).
- **Couleurs Majeures :**
  - **Bleu Nuit Profond** (`#03045E`) : Titres principaux, autorité, pied de page.
  - **Bleu Océan** (`#0077B6` / `#0096C7`) : Boutons d'action majeurs, accents interactifs.
  - **Bleu Céleste** (`#48CAE4` / `#90E0EF`) : Badges, survol, citations.
  - **Fond Papier Chaud** (`#FAF9F6`) : Confort de lecture spirituelle.
- **Zéro Cliché AI :** Pas de boîtes à pilules statiques inutiles, hiérarchie éditoriale naturelle, respect des règles WCAG AA de contraste.

---

## 🚀 Fonctionnalités Détaillées

### 1. Navigation & En-tête (Top Bar Contract)
- **Wordmark :** *La Parole au Quotidien* avec logo gravé.
- **Liens principaux :** *Accueil*, *Explorer les Articles* (2e page majeure), *Leçon du Jour*, *Trimestres*, *Les 10 Blogs*, *Séries & Leçons*.
- **Barre de recherche instantanée :** Recherche en direct sur les versets, auteurs et doctrines.
- **Cercle d'Avatar Indicatif :** Cercle en haut à droite avec les initiales du compte actif, menu déroulant et modale de personnalisation du profil (*Nom, @username, E-mail, Rôle, Couleur, Bio*).

### 2. Bibliothèque Communautaire (Seconde Page Principale)
- Vue consolidée de tous les articles et leçons publiés par les différents auteurs.
- Filtres combinables : par Thème, par Trimestre d'étude, par Auteur.
- Filtre rapide **« Mes Favoris »**.
- Tri par *Plus récents*, *Plus anciens*, ou *Les plus commentés*.
- Compteur de commentaires et temps de lecture sur chaque carte.

### 3. Écran de Lecture Immersif
- Rendu HTML sécurisé (nettoyage DOMPurify strict empêchant les failles XSS).
- **Conservation des couleurs des versets bibliques** appliquées par les auteurs.
- Lecteur audio intégré (synthèse vocale) pour écouter la leçon en voyage.
- Ajustement de taille de texte en 3 crans (A, A+, A++).
- Bouton de mise en favori et bouton de copie de lien de partage.
- Formulaire de commentaires avec enregistrement automatique sous le statut `pending`.

### 4. Back-office Auteur & Administrateur
- **Connexion Sécurisée :** Masquage/révélation du mot de passe, mémorisation, verrouillage anti-bruteforce après 5 échecs, et comptes pré-remplis pour tests rapides.
- **Tableau de Bord :** Indicateurs KPIs, console de modération des commentaires (*Approuver / Rejeter / Supprimer*), gestion de l'article mis en vedette.
- **Éditeur WYSIWYG & Coloration :**
  - Outils de titres H2/H3, gras, italique, souligné, listes et encadrés de versets.
  - Palette spirituelle de coloration de texte pour surligner les passages clés.
  - Auto-sauvegarde locale toutes les 30 secondes dans le `localStorage`.
  - **Module d'Importation Externe :** Nettoyage automatique du texte ou HTML collé depuis Word/Email, détection automatique du titre et extraction du verset.

---

## 🛠️ Stack Technique

- **Frontend :** [React 19](https://react.dev) + [TypeScript](https://www.typescriptlang.org)
- **Build Tool :** [Vite 8](https://vitejs.dev)
- **Styling :** [Tailwind CSS 4](https://tailwindcss.com)
- **Icons :** [Lucide React](https://lucide.dev)
- **Animations :** [Motion](https://motion.dev)
- **Sécurité HTML :** [DOMPurify](https://github.com/cure53/DOMPurify)
- **Polices Web :** Google Fonts (*Anton*, *Fira Sans*, *JetBrains Mono*)
- **Persistance :** LocalStorage réactif avec synchronisation de session et état d'auto-sauvegarde.

---

## 💻 Installation & Démarrage Local

### Prérequis
- [Node.js](https://nodejs.org) (version 18 ou supérieure recommandée)
- [npm](https://www.npmjs.com) ou [yarn](https://yarnpkg.com)

### 1. Cloner le dépôt
```bash
git clone https://github.com/votre-compte/la-parole-au-quotidien.git
cd la-parole-au-quotidien
```

### 2. Installer les dépendances
```bash
npm install
```

### 3. Lancer le serveur de développement
```bash
npm run dev
```
L'application sera accessible sur `http://localhost:3000`.

### 4. Compiler pour la production
```bash
npm run build
```
Les fichiers statiques optimisés seront générés dans le dossier `/dist`.

### 5. Prévisualiser le build de production
```bash
npm run preview
```

---

## 🔑 Identifiants de Démonstration (Back-office)

Pour tester immédiatement l'espace rédaction et la modération des commentaires sans créer de compte, utilisez les profils de démonstration pré-configurés :

| Profil | E-mail | Mot de passe | Rôle & Permissions |
|--------|--------|--------------|-------------------|
| **Pasteur Élie Maranatha** | `admin@laparole.org` | `admin123` | **Administrateur** (accès complet, modération, publication, mise en avant) |
| **Dr. Sarah Ben-David** | `redacteur@laparole.org` | `foi2026` | **Rédacteur / Auteur** (création, édition d'articles et import) |

*(Des boutons de connexion rapide en 1 clic sont également disponibles sur l'écran de connexion).*

---

## 🌐 Déploiement en Production

### Option A : Déploiement sur Vercel (Recommandé)
1. Importez votre dépôt GitHub sur [Vercel](https://vercel.com).
2. Paramètres détectés :
   - **Framework Preset :** `Vite`
   - **Build Command :** `npm run build`
   - **Output Directory :** `dist`
3. Cliquez sur **Deploy**.

### Option B : Déploiement sur Netlify
1. Connectez votre dépôt sur [Netlify](https://www.netlify.com).
2. Renseignez :
   - **Build command :** `npm run build`
   - **Publish directory :** `dist`
3. Déployez le site.

### Option C : Hébergement Google Cloud Run / Docker
Le projet peut être servi par un conteneur léger Nginx ou un serveur Express statique.

---

## 📂 Structure des Fichiers

```text
├── index.html                   # Entrée HTML avec polices Anton & Fira Sans
├── metadata.json                # Métadonnées officielles du projet
├── package.json                 # Dépendances et scripts de build
├── tsconfig.json                # Configuration TypeScript
├── vite.config.ts               # Configuration Vite
├── src/
│   ├── main.tsx                 # Point de montage React
│   ├── App.tsx                  # Routage principal & gestion des vues
│   ├── index.css                # Styles globaux, variables Tailwind et typographie
│   ├── types/
│   │   └── index.ts             # Interfaces TypeScript (Article, Theme, Comment, UserProfile...)
│   ├── data/
│   │   └── initialData.ts       # Données de départ (10 blogs, trimestres, articles et commentaires)
│   ├── services/
│   │   └── storage.ts           # Service de persistance LocalStorage, assainissement HTML et import
│   ├── components/
│   │   ├── Header.tsx           # Barre de navigation, recherche, favoris et avatar circulaire
│   │   ├── Footer.tsx           # Pied de page avec liens vers les 10 blogs et mission
│   │   ├── NewsletterSection.tsx# Bloc d'inscription à la leçon quotidienne
│   │   └── ProfileEditModal.tsx # Fenêtre de modification du profil (@username, nom, email, couleur...)
│   └── views/
│       ├── HomeView.tsx         # Accueil : Hero, Leçon du jour, 10 blogs, trimestres, séries
│       ├── ArticlesExplorerView.tsx # 2e page principale : bibliothèque communautaire, filtres & favoris
│       ├── ArticleDetailView.tsx    # Page de lecture immersive, audio, versets colorés, commentaires
│       ├── ThemeArticlesView.tsx    # Page dédiée listant tous les articles d'un thème précis
│       ├── QuartersView.tsx         # Navigation et archives par trimestres d'étude
│       ├── SeriesView.tsx           # Parcours d'études bibliques sur plusieurs jours
│       ├── SearchView.tsx           # Page de résultats de recherche plein texte
│       └── admin/
│           ├── LoginView.tsx        # Connexion sécurisée au back-office
│           ├── DashboardView.tsx    # Tableau de bord, statistiques et modération des commentaires
│           └── ArticleEditorView.tsx# Éditeur WYSIWYG, versets colorés, auto-sauvegarde et import
```

---

## 📜 Licence & Droits

Ce projet est distribué sous la licence **Apache 2.0**. Vous êtes libre de l'utiliser, le modifier et le déployer pour l'édification spirituelle de votre communauté.

---

*« Ta parole est une lampe à mes pieds, et une lumière sur mon sentier. » — Psaume 119:105*
