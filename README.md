# Liberchat Site Web

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Yes-brightgreen)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![Open Source](https://img.shields.io/badge/Open%20Source-❤️-red)](https://opensource.org/)
[![Discord](https://img.shields.io/discord/YOUR_DISCORD_ID?color=7289da&label=Discord&logo=discord&logoColor=white)](https://discord.gg/nQDz6g8nYZ)
[![GitHub Stars](https://img.shields.io/github/stars/AnARCHIS12/liberchat-site?style=social)](https://github.com/AnARCHIS12/liberchat-site)

Site web officiel de Liberchat - Application de messagerie libre et sécurisée.




## 📋 Fonctionnalités du site

- **Page d'accueil** - Présentation de Liberchat et téléchargements
- **Feuille de route** - Évolution du projet et versions futures
- **FAQ** - Questions fréquentes avec système d'accordéon
- **Mentions légales** - Politique de confidentialité et conformité RGPD
- **Pages de téléchargement** - Pour chaque plateforme (Windows, Linux, macOS, Android)
- **Auto-hébergement** - Guide pour héberger son propre serveur (YunoHost)
- **Docker** - Test en local et développement rapide
- **Design responsive** - Compatible mobile et desktop

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Styles modernes avec variables CSS
- **JavaScript** - Interactions et animations
- **Font Awesome** - Icônes
- **Google Fonts** - Typographie (Inter)

## 📁 Structure du projet

```
liberchat/
├── index.html              # Page d'accueil
├── roadmap.html            # Feuille de route
├── faq.html                # Questions fréquentes
├── privacy.html            # Mentions légales
├── releases.html           # Téléchargements Android
├── releases-linux.html     # Téléchargements Linux
├── releases-windows.html   # Téléchargements Windows
├── releases-macos.html     # Téléchargements macOS
├── installation-apk.html   # Guide installation mobile
├── autohebergement.html    # Guide auto-hébergement YunoHost
├── docker.html             # Guide Docker pour développement
├── qr.html                 # QR codes pour mobile
├── styles.css              # Styles principaux
├── script.js               # Scripts JavaScript
├── modern-interactions.js  # Animations avancées
├── assets/                 # Images et ressources
│   └── icon.png           # Logo Liberchat
├── README.md              # Ce fichier
└── LICENSE                # Licence du projet
```

## 🚀 Installation locale

1. **Cloner le repository**
   ```bash
   git clone https://github.com/AnARCHIS12/liberchat-site.git
   cd liberchat-site
   ```

2. **Serveur local**
   ```bash
   # Avec Python
   python -m http.server 8000
   
   # Avec Node.js
   npx serve .
   
   # Avec PHP
   php -S localhost:8000
   ```

3. **Ouvrir dans le navigateur**
   ```
   http://localhost:8000
   ```

## 🎨 Personnalisation

### Variables CSS
Le site utilise des variables CSS pour faciliter la personnalisation :

```css
:root {
  --primary-color: #007bff;
  --accent-color: #28a745;
  --background-color: #1a1a1a;
  --text-color: #ffffff;
  --card-background: #2d2d2d;
}
```

### Thèmes
- **Thème sombre** - Par défaut
- **Mode responsive** - Adaptation automatique mobile/desktop
- **Animations** - Transitions fluides et effets hover

## 📱 Compatibilité

- **Navigateurs modernes** - Chrome, Firefox, Safari, Edge
- **Responsive design** - Mobile, tablette, desktop
- **Performance** - Optimisé pour le chargement rapide
- **Accessibilité** - Standards WCAG respectés

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. **Fork** le projet
2. **Créer** une branche pour votre fonctionnalité
3. **Commit** vos changements
4. **Push** vers la branche
5. **Ouvrir** une Pull Request

### Guidelines
- Respecter la structure HTML sémantique
- Utiliser les variables CSS existantes
- Tester sur mobile et desktop
- Optimiser les images et ressources

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 🔗 Liens utiles

- **Application Liberchat** - [GitHub](https://github.com/AnARCHIS12/Liberchat-3.0)
- **Auto-hébergement YunoHost** - [GitHub](https://github.com/Liberchat/liberchatserver_ynh)
- **Docker** - [GitHub](https://github.com/Liberchat/Liberchat-docker)
- **Discord** - [Rejoindre la communauté](https://discord.gg/nQDz6g8nYZ)
- **Facebook** - [Groupe Facebook](https://www.facebook.com/groups/1056100956078058)
- **Téléchargements** - [Releases](https://github.com/Liberchat)

## 📞 Contact

- **Discord** - Communauté active 24/7
- **GitHub Issues** - Pour les bugs et suggestions
- **Email** - anarchymedialibertaire@gmail.com

---

**Liberchat** - Communication libre et sécurisée pour tous 🔒
