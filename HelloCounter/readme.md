# README – Génération et installation de l’APK Debug

## Objectif
Générer l’APK debug de l’application et vérifier son installation sur un appareil ou émulateur Android.

## Génération de l’APK
1. Ouvrir le projet dans Android Studio.
2. Aller dans **Build → Build APK(s)**.
3. L’APK se trouve dans : `app/build/outputs/apk/debug/app-debug.apk`.

## Installation de l’APK
### Option 1 – Avec Android Studio
1. Connecter un appareil Android ou lancer un émulateur.
2. Cliquer sur **Run ▶** et sélectionner l’appareil ou l’émulateur.

### Option 2 – Avec ADB
1. Ouvrir un terminal et aller dans le dossier de l’APK.
2. Lancer la commande : `adb install app-debug.apk`.

## Vérification
- Lancer l’application pour vérifier qu’elle fonctionne correctement.

## Livrables
- Fichier **app-debug.apk**
- Ce **README.md** avec les étapes ci-dessus
