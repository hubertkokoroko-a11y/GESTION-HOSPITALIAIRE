# 🏥 Hôpital EL-ELYON - Système de Gestion Hospitalière

Système complet de gestion des hospitalisations développé pour l'Hôpital EL-ELYON.

## 🚀 Fonctionnalités

- ✅ **Tableau de bord** : Vue d'ensemble des patients, chambres et assurances
- ✅ **Gestion des chambres** : Ajout, suppression et suivi des chambres
- ✅ **Admission patient** : Enregistrement avec type d'assurance (AMU, INAM, ASCOMA, etc.)
- ✅ **Gestion des assurances** : Configuration des prises en charge avec tranches de prix
- ✅ **Exéat & Décès** : Gestion des sorties et décès avec dates
- ✅ **Historique** : Traçabilité complète des mouvements
- ✅ **Synchronisation temps réel** : Données partagées entre tous les utilisateurs via Firebase
- ✅ **Impression** : Rapports imprimables
- ✅ **Authentification** : Protection par mot de passe

## 🔐 Accès

- **Mot de passe par défaut** : `admin`

## 📦 Déploiement sur GitHub Pages

1. Créez un dépôt GitHub public
2. Uploadez les fichiers `index.html` et `README.md`
3. Allez dans **Settings > Pages**
4. Sélectionnez la branche `main` et le dossier `/ (root)`
5. Votre site sera accessible à : `https://votre-username.github.io/nom-du-repo/`

## 🔥 Configuration Firebase (OBLIGATOIRE)

Pour que plusieurs personnes voient les mêmes données en temps réel :

1. Allez sur [console.firebase.google.com](https://console.firebase.google.com)
2. Créez un nouveau projet
3. Activez **Firestore Database** (mode test)
4. Créez une application Web et copiez les clés de configuration
5. Ouvrez `index.html` dans un éditeur de texte
6. Remplacez le bloc `firebaseConfig` par vos propres clés
7. Enregistrez et republiez

## 🛠️ Technologies

- HTML5 / CSS3 (Tailwind CSS)
- JavaScript (ES6 Modules)
- Firebase Firestore (Base de données temps réel)
- Font Awesome (Icônes)

## 📝 Licence

© 2026 Hôpital EL-ELYON - Tous droits réservés