# Liberchat Site Web

Site web officiel de Liberchat - Application de messagerie libre et sécurisée.

## 🌐 Aperçu

Ce repository contient le code source du site web officiel de Liberchat, une application de messagerie décentralisée avec chiffrement de bout en bout.

**URL du site :** [liberchat.org](https://liberchat.org)

## 📋 Fonctionnalités du site

- **Page d'accueil** - Présentation de Liberchat et téléchargements
- **Feuille de route** - Évolution du projet et versions futures
- **FAQ** - Questions fréquentes avec système d'accordéon
- **Mentions légales** - Politique de confidentialité et conformité RGPD
- **Pages de téléchargement** - Pour chaque plateforme (Windows, Linux, macOS, Android)
- **Auto-hébergement** - Guide pour héberger son propre serveur
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
├── autohebergement.html    # Guide auto-hébergement
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
- **Discord** - [Rejoindre la communauté](https://discord.gg/nQDz6g8nYZ)
- **Facebook** - [Groupe Facebook](https://www.facebook.com/groups/1056100956078058)
- **Téléchargements** - [Releases](https://github.com/Liberchat)

## 📞 Contact

- **Discord** - Communauté active 24/7
- **GitHub Issues** - Pour les bugs et suggestions
- **Email** - contact@liberchat.org

---

**Liberchat** - Communication libre et sécurisée pour tous 🔒