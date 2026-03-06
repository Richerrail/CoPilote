# CoPilot - Compagnon de Route Vocal Québécois

App Android native en React Native avec support Bluetooth complet.

## Installation rapide avec Expo

### 1. Prépare ton ordi

Ouvre un terminal et installe Expo CLI :
```bash
npm install -g expo-cli eas-cli
```

### 2. Crée un compte Expo

Va sur **expo.dev** et crée un compte gratuit.

Ensuite connecte-toi dans le terminal :
```bash
npx expo login
```

### 3. Installe Expo Go sur ton cell

- Android : **Google Play Store** → cherche **"Expo Go"** → installe
- iOS : **App Store** → cherche **"Expo Go"** → installe

### 4. Lance l'app

Dans le dossier de l'app, lance :
```bash
cd copilot-app
npm install
npx expo start
```

Un QR code va apparaître. **Scan-le avec Expo Go** sur ton cell.

L'app va se charger direct sur ton téléphone — aucune compilation nécessaire!

---

## Build un vrai APK (optionnel, si tu veux installer sans Expo Go)

Si tu veux un fichier `.apk` à installer directement :

```bash
eas build --platform android --profile preview
```

Ça compile dans le cloud, puis tu reçois un lien pour télécharger l'APK sur ton cell.

Si tu veux tester toute suite sans avoir a compiler l'APK est disponible dans release en version beta!!!!

---

## Problèmes courants

**"Module not found"** → Lance `npm install` dans le dossier

**QR code ne scan pas** → Vérifie que ton cell et ordi sont sur le même WiFi

**Expo Go crash** → Efface l'app Expo Go, réinstalle-la

---

## Permissions Bluetooth

L'app demande automatiquement :
- Accès micro
- Bluetooth
- Keep screen awake

Accepte toutes les permissions la première fois.

---

**C'est tout!** Une fois que l'app roule dans Expo Go, connecte ton Bluetooth et démarre une session.
