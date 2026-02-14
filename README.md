![CoPilote - Compagnon vocal de route](assets/banner.png)

# CoPilote

**CoPilote** est ton chum IA vocal québécois qui ride shotgun avec toi dans le char.  
Il te garde éveillé sur la route avec du jasage naturel, de l'humour rough, des débats sans filtre et des checks discrets anti-dodo.  
Construit 100% web (HTML/CSS/JS) avec reconnaissance vocale + synthèse vocale du navigateur + DeepSeek pour le cerveau.

Ton site live :  
👉 https://richerraill.github.io/CoPilote/

## Aperçu

Voici l'interface en action (mode sombre, gros bouton micro qui pulse en rouge quand il écoute/parle) :

![Capture d'écran de CoPilote - Interface principale](assets/screenshot.png)

- Écran de démarrage avec saisie de clé API DeepSeek (sauvegardée localement)  
- Chat vocal en continu (tu parles, il répond avec une voix québécoise réaliste)  
- Animations sonar + wave pour le feeling "live"

## Fonctionnalités principales

- **Voix québécoise naturelle** : accent, expressions (fak, chus, une shot, boutte, etc.)  
- **Personnalité** : chum direct, humour noir/absurde (style Mike Ward / Denis Drolet), adore débattre politique/religion/tabous  
- **Anti-fatigue** : check discret toutes les ~8-10 échanges, alerte sérieuse si tu dis que t'es trop fatigué  
- **Reconnaissance vocale** : Web Speech API (meilleur sur Chrome/Edge Android)  
- **Synthèse vocale** : voix fr-CA réaliste (rate/pitch ajustés pour sonner naturel)  
- **Session persistante** : historique court pour garder le contexte  
- **Wake Lock** : écran reste allumé pendant la session  

## Technologies utilisées

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![DeepSeek](https://img.shields.io/badge/DeepSeek-000000?style=for-the-badge&logo=ai&logoColor=white)
![Web Speech API](https://img.shields.io/badge/Web%20Speech%20API-4285F4?style=for-the-badge&logo=google&logoColor=white)

- HTML + CSS pur (dark mode, animations CSS)  
- JavaScript vanilla (pas de framework)  
- DeepSeek API pour les réponses intelligentes  
- Web Speech Recognition + SpeechSynthesis (navigateur natif)

## Comment l'utiliser

1. Va sur https://richerraill.github.io/CoPilote/  
2. Entre ta clé API DeepSeek (gratuite sur https://platform.deepseek.com)  
3. Appuie sur le gros bouton micro → CoPilot se réveille et commence à jaser  
4. Parle normalement (français québécois recommandé pour le fun)  
5. Reclique pour arrêter la session quand tu arrives

**Note** : Meilleur rendu sur **Chrome ou Edge mobile** (Android). Safari/iOS support partiel pour la reco vocale.

## Contribuer ou me parler

Bug ? Idée d'amélioration ? Nouvelle joke dark à tester ?  
Ouvre une **Issue** ou fork le repo !

Tu peux aussi me contacter sur [LinkedIn](https://linkedin.com/in/ton-profil) ou ailleurs.

## Licence

MIT License – fais-en ce que tu veux (mais garde le crédit si tu le partages svp).  
Voir le fichier [LICENSE](LICENSE) pour les détails.

---

Bonne route, pis reste éveillé ! 🚗🔊  
⭐ Si ça te plaît, mets une petite étoile au repo !
