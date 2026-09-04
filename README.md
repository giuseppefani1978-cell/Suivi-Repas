# 🥗 Diet & Symptom Tracker / Journal Diète & Symptômes

[Français](#-version-française) | [English](#-english-version)

---

## 🇫🇷 Version Française

Une Progressive Web App (PWA) légère, autonome et respectueuse de votre vie privée, conçue pour répertorier vos repas (avec photos et saisie vocale) et corréler l'apparition de vos symptômes digestifs ou intolérances alimentaires dans le temps.

### ✨ Fonctionnalités clés

- **📸 Prise de photo & compression automatique :** Capture directe depuis l'appareil photo du smartphone avec compression JPEG à la volée (optimisation de l'espace de stockage).
- **🎤 Saisie vocale native :** Dictée vocale instantanée de vos ingrédients et ressentis sans configuration complexe (via la *Web Speech API*).
- **💾 Stockage local pérenne (IndexedDB) :** Vos données et photos restent strictement stockées sur votre appareil, sans aucun serveur tiers ni abonnement.
- **⏱️ Suivi temporel des symptômes :** Enregistrement des réactions à différents intervalles temporels (immédiat, 2 h, 4 h, lendemain).
- **📤 Export & Partage instantané (WhatsApp, Email) :**
  - **Export CSV :** Compatible Excel / tableurs pour un suivi médical ou nutritionnel.
  - **Rapport HTML autonome :** Document complet incluant l'historique et toutes les photos miniatures intégrées.
- **📱 Mode Application (PWA) :** Installable directement sur l'écran d'accueil iOS et Android sans passer par les stores d'applications.

---

### 🚀 Déploiement rapide

Cette application ne nécessite aucun backend ni base de données distante. Un simple hébergement de fichiers statiques suffit.

#### Option 1 : GitHub Pages (Recommandé)
1. Créez un nouveau dépôt public ou privé sur GitHub.
2. Déposez-y le fichier `index.html` et ce `README.md`.
3. Allez dans les **Settings** de votre dépôt > **Pages**.
4. Sous **Build and deployment**, sélectionnez la branche `main` (ou `master`) et le dossier `/ (root)`, puis cliquez sur **Save**.
5. Votre application sera accessible via l'URL fournie par GitHub (`https://<votre-nom>.github.io/<nom-du-repo>/`).

#### Option 2 : Netlify / Vercel
- Glissez-déposez simplement le dossier contenant `index.html` sur [Netlify Drop](https://app.netlify.com/drop). Le site sera en ligne en quelques secondes avec HTTPS activé.

---

### 📱 Installation sur smartphone

Pour éviter la purge automatique du cache et utiliser l'outil comme une application native :
- **Sur iPhone (Safari) :**
  1. Ouvrez l'URL de votre application dans Safari.
  2. Appuyez sur le bouton de partage (icône avec un carré et une flèche vers le haut).
  3. Faites défiler vers le bas et sélectionnez **Sur l'écran d'accueil**.
- **Sur Android (Chrome) :**
  1. Ouvrez l'URL dans Google Chrome.
  2. Appuyez sur les trois points verticaux en haut à droite.
  3. Sélectionnez **Ajouter à l'écran d'accueil** ou **Installer l'application**.

---

### 🔒 Vie privée & Sécurité des données

- Toutes les données (textes, horodatages, photos compressées) sont enregistrées localement dans la base de données interne de votre navigateur (**IndexedDB**).
- Aucun cookie traceur, aucun service d'analyse tiers et aucune fuite de données vers des serveurs distants.
- Pensez à faire des sauvegardes régulières via les boutons d'export CSV / HTML.

---

<br>

## 🇬🇧 English Version

A lightweight, standalone, privacy-focused Progressive Web App (PWA) designed to log meals (with photos and speech-to-text) and correlate digestive symptoms or food intolerances over time.

### ✨ Key Features

- **📸 Camera & Client-side Image Compression:** Capture food photos directly on mobile, compressed in real-time to save device storage.
- **🎤 Native Speech Recognition:** Dictate meals and symptoms hands-free using the browser's built-in *Web Speech API*.
- **💾 Offline-First Storage (IndexedDB):** All records and photos are stored securely inside your browser's local database. No backend or subscriptions required.
- **⏱️ Time-delayed Symptom Tracking:** Monitor physical reactions across custom delays (immediate, 2 hours, 4 hours, next day).
- **📤 Easy Sharing & Export (WhatsApp, Email):**
  - **CSV Export:** Clean tabular data formatted for Excel or healthcare providers.
  - **Self-contained HTML Report:** Visual log embedding all meal thumbnails for easy review.
- **📱 Installable PWA:** Add to Home Screen on iOS and Android for a native app experience.

---

### 🚀 Quick Deployment

No server-side runtime, dependencies, or APIs needed. Just serve the static `index.html`.

#### Option 1: GitHub Pages
1. Create a repository on GitHub.
2. Push `index.html` and `README.md`.
3. Go to **Settings** > **Pages**.
4. Set source to the `main` branch and `/ (root)`, then click **Save**.
5. Your app will be live at `https://<username>.github.io/<repo-name>/`.

#### Option 2: Netlify / Vercel
- Drag and drop your project directory directly into [Netlify Drop](https://app.netlify.com/drop).

---

### 📱 Mobile Installation

To prevent browser cache eviction and enjoy full offline support:
- **iOS (Safari):** Tap the **Share** button > select **Add to Home Screen**.
- **Android (Chrome):** Tap the menu icon (three dots) > select **Add to Home screen** / **Install app**.

---

### 🔒 Privacy & Data Retention

- 100% client-side storage powered by **IndexedDB**.
- Zero external tracking, zero third-party telemetry, zero cloud storage.
- We recommend performing periodic CSV or HTML backups to keep your medical journal safe.

---

## 📄 Licence / License

Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.  
This project is licensed under the MIT License.
