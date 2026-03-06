# CoPilot - Build avec GitHub Actions

## Setup (une seule fois)

### 1. Crée un compte Expo

Va sur **expo.dev** → Sign up (gratuit)

### 2. Génère un token Expo

1. Va sur https://expo.dev/accounts/[ton-username]/settings/access-tokens
2. Clique **"Create Token"**
3. Nom: `GITHUB_ACTIONS`
4. **Copie le token** (tu le verras qu'une fois)

### 3. Crée un repo GitHub

1. Va sur **github.com** → New repository
2. Nom: `copilot-app`
3. **Public** ou **Private** (les deux marchent)
4. **Ne coche rien** (pas de README, pas de .gitignore)
5. Clique **Create repository**

### 4. Ajoute le token Expo à GitHub

1. Dans ton repo GitHub → **Settings** (en haut)
2. **Secrets and variables** → **Actions**
3. **New repository secret**
4. Name: `EXPO_TOKEN`
5. Value: **colle ton token Expo**
6. **Add secret**

### 5. Push le code sur GitHub

Dans ton terminal (dossier `copilot-app`) :

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TON-USERNAME/copilot-app.git
git push -u origin main
```

**Remplace `TON-USERNAME`** par ton vrai username GitHub.

---

## Ça y est! 🎉

Le build se lance **automatiquement** dans le cloud.

### Voir le build en cours :

1. Va sur ton repo GitHub
2. Clique sur **Actions** (en haut)
3. Tu vas voir le build en cours

Le build prend **10-15 minutes**.

### Récupérer l'APK :

Une fois terminé :

1. Va sur **expo.dev/accounts/[ton-username]/projects/copilot-app/builds**
2. Clique sur le dernier build
3. **Download** l'APK
4. Ouvre le fichier sur ton cell Android
5. Installe (autorise "sources inconnues" si demandé)

---

## Rebuild plus tard

Pour rebuilder après des modifications :

```bash
git add .
git commit -m "Update app"
git push
```

GitHub Actions rebuild automatiquement!

---

## Troubleshooting

**"remote: Repository not found"**
→ Vérifie que tu as remplacé `TON-USERNAME` par ton vrai username

**"Please make sure you have the correct access rights"**
→ Configure SSH ou utilise HTTPS avec ton mot de passe GitHub

**Build fail sur GitHub Actions**
→ Vérifie que le secret `EXPO_TOKEN` est bien ajouté dans Settings → Secrets

---

**C'est tout!** Une fois setup, chaque push compile automatiquement l'APK dans le cloud.
