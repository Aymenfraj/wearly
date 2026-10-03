# WEARLY Android

Projet Android Studio prêt pour GitHub.

## Important
Le prototype WEARLY existant est un fichier HTML/CSS/JavaScript. Le wrapper Android utilise un WebView pour le transformer en application Android.

### 1. Mettre le prototype
Remplace:
`app/src/main/assets/wearly-v2.html`
par le fichier complet `wearly-v2.html` de ton prototype.

### 2. Ouvrir dans Android Studio
File > Open > sélectionner le dossier `WEARLY-Android`.

### 3. Tester
Brancher un téléphone Android avec le mode développeur/USB debugging activé puis:
Run > Run 'app'

### 4. Générer l'APK
Build > Generate App Bundles or APKs > Generate APKs

L'APK de debug sera normalement dans:
`app/build/outputs/apk/debug/app-debug.apk`

## GitHub
Créer un dépôt, puis:
git init
git add .
git commit -m "Initial WEARLY Android"
git branch -M main
git remote add origin TON_URL_GITHUB
git push -u origin main

## Évolution recommandée
Ce premier APK est un wrapper du prototype. Ensuite on pourra remplacer le WebView par une vraie application native/Capacitor et connecter:
- météo réelle
- GPS
- caméra + reconnaissance vêtements
- comptes utilisateurs
- base de données
- vendeurs
- stock/prix réels
- chat
- paiement
- notifications
