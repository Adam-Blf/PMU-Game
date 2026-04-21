[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adambeloucif/) ![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=Adam-Blf.PMU-Game)


![Dernier commit](https://img.shields.io/github/last-commit/Adam-Blf/PMU-Game?style=flat&logo=git&logoColor=white&color=0080ff&label=Dernier%20commit) ![Langage principal](https://img.shields.io/github/languages/top/Adam-Blf/PMU-Game?style=flat&logo=git&logoColor=white&color=0080ff&label=Langage%20principal) ![Nombre de langages](https://img.shields.io/github/languages/count/Adam-Blf/PMU-Game?style=flat&logo=git&logoColor=white&color=0080ff&label=Nombre%20de%20langages)

## 📝 Description
Simulation de paris hippiques (PMU).

## ⚡ Fonctionnalités
- Simulation de courses
- Système de paris
- Gestion de budget


### Construit avec les outils et technologies : 

![CSS](https://img.shields.io/badge/-CSS-0080ff?style=flat) ![JavaScript](https://img.shields.io/badge/-JavaScript-0080ff?style=flat) ![HTML](https://img.shields.io/badge/-HTML-0080ff?style=flat)

🇫🇷 Français | 🇬🇧 Anglais | 🇪🇸 Espagnol | 🇮🇹 Italien | 🇵🇹 Portugais | 🇷🇺 Russe | 🇩🇪 Allemand | 🇹🇷 Turc

# 🏇 Le PMU - Jeu d'Alcool avec Cartes

![Status](https://img.shields.io/badge/status-complete-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![GH Pages](https://img.shields.io/badge/play-GH_Pages-222?logo=github&logoColor=white)
![MIT](https://img.shields.io/badge/license-MIT-blue)

> Jeu d'alcool interactif basé sur des courses de chevaux avec cartes. Misez, pariez et distribuez des gorgées ! Application web moderne sans dépendances externes.

[🎮 Jouer en ligne](#) | [📖 Documentation](#règles-du-jeu) | [🎯 Règles](#règles-du-jeu)

---

## 📝 Description

**Le PMU** est un jeu d'alcool convivial où les joueurs parient des gorgées sur des chevaux représentés par les 4 couleurs de cartes (♠️ Pique, ♥️ Cœur, ♦️ Carreau, ♣️ Trèfle). À chaque carte tirée, le cheval correspondant avance. Le premier qui dépasse la ligne d'arrivée fait gagner les paris !

### ✨ Fonctionnalités

- ✅ **Interface moderne** : Design responsive avec animations
- ✅ **Jeu interactif** : Cliquez pour tirer les cartes et faire avancer les chevaux
- ✅ **Système de paris** : Chaque joueur répartit ses gorgées sur les chevaux
- ✅ **Bonus à 5 cartes** : Pariez 3 gorgées supplémentaires (risque double si perte)
- ✅ **Statistiques** : Suivi des victoires de chaque cheval
- ✅ **Configuration flexible** : Nombre de joueurs, gorgées, longueur de course
- ✅ **Multi-joueurs** : 2 à 8 joueurs
- ✅ **Aucune dépendance** : HTML/CSS/JS pur

---

## 🎯 Règles du Jeu

### 📋 Préparation

1. **Nombre de joueurs** : 2 à 8 personnes
2. **Budget** : Chaque joueur dispose de **5 gorgées** à miser par course
3. **Chevaux** : 4 chevaux représentés par les couleurs de cartes
   - ♠️ **Pique** (Noir)
   - ♥️ **Cœur** (Rouge)
   - ♦️ **Carreau** (Rouge)
   - ♣️ **Trèfle** (Noir)

### 🎲 Déroulement

1. **Mises** : Chaque joueur répartit ses 5 gorgées sur un ou plusieurs chevaux
2. **Course** : Le croupier tire les cartes une par une
3. **Avancement** : Le cheval correspondant à la couleur de la carte avance d'un slot
4. **Bonus (optionnel)** : À 5 cartes tirées, possibilité de parier 3 gorgées bonus sur un seul cheval
   - Si le cheval gagne : distribue 3 gorgées
   - Si le cheval perd : boit 6 gorgées (double)
5. **Victoire** : Le premier cheval qui dépasse la ligne d'arrivée gagne

### 🏆 Distribution des gorgées

- Les joueurs ayant parié sur le **cheval gagnant** distribuent le **nombre de gorgées misées** sur ce cheval
- Les joueurs ayant perdu leur **bonus** boivent **6 gorgées**

### 🎯 Stratégies

- **Sécurité** : Répartir équitablement sur plusieurs chevaux
- **Risque** : Tout miser sur un seul cheval pour maximiser les distributions
- **Bonus** : Utiliser le bonus pour renverser la situation

---

## 🚀 Installation et Utilisation

### 🌐 Utilisation en ligne

Ouvrez simplement `index.html` dans votre navigateur web préféré. Aucune installation requise !

### 💻 Installation locale

```bash
# Cloner le repository
git clone https://github.com/Adam-Blf/PMU-Game.git
cd PMU-Game

# Ouvrir dans le navigateur
# Méthode 1: Double-clic sur index.html

# Méthode 2: Serveur local avec Python
python -m http.server 8000
# Puis ouvrir http://localhost:8000

# Méthode 3: Serveur local avec Node.js
npx http-server
# Puis ouvrir http://localhost:8080
```

### 🎮 Démarrage rapide

1. **Configuration**
   - Choisir le nombre de joueurs (2-8)
   - Définir le budget par joueur (5-50 gorgées)
   - Ajuster la longueur de la course (5-12 slots)
   - Activer/désactiver le bonus

2. **Miser**
   - Chaque joueur place ses paris sur les chevaux
   - Utiliser les boutons +/- pour ajuster les mises

3. **Jouer**
   - Cliquer sur "Tirer une carte" pour faire avancer un cheval
   - À 5 cartes (si activé), placer un bonus
   - Continuer jusqu'à ce qu'un cheval gagne

4. **Résultat**
   - Le modal affiche le cheval gagnant
   - Distribuer/boire les gorgées selon les paris

---

## 🛠️ Technologies

- **HTML5** : Structure sémantique
- **CSS3** : Design moderne avec gradients, animations, responsive
- **JavaScript (ES6+)** : Logique de jeu, gestion d'état, DOM manipulation
- **Font Awesome 6** : Icônes (CDN)

### 📂 Structure du projet

```
PMU-Game/
├── index.html          # Structure HTML
├── style.css           # Styles CSS (responsive design)
├── app.js              # Logique JavaScript du jeu
├── README.md           # Documentation
├── LICENSE             # Licence MIT
└── screenshots/        # Captures d'écran (optionnel)
```

---

## 🎨 Captures d'écran

### 🏠 Écran de configuration
Interface de réglage avec :
- Sélection du nombre de joueurs
- Configuration des gorgées
- Longueur de la course
- Règles du jeu

### 🏁 Plateau de jeu
Vue de la course avec :
- Piste de course visuelle
- 4 chevaux (♠️ ♥️ ♦️ ♣️)
- Panneau de paris par joueur
- Statistiques en temps réel

### 🏆 Écran de résultat
Modal de victoire affichant :
- Cheval gagnant
- Distribution des gorgées
- Bonus gagnés/perdus

---

## 🎯 Variantes du Jeu

Le jeu propose plusieurs variantes personnalisables :

1. **Budget variable** : Augmenter les gorgées à 10, 15, 20...
2. **Course longue** : Ajouter des slots pour des courses plus longues
3. **Mono-pari** : Forcer les joueurs à choisir UN seul cheval
4. **Cartes pièges** : Ajouter des cartes cachées qui font reculer
5. **Budget aléatoire** : Chaque joueur tire un budget au hasard
6. **Tournoi** : Faire plusieurs courses et compter les points

---

## 🎲 Règles Avancées

### Bonus à 5 cartes
- **Activation** : Cocher l'option dans les réglages
- **Moment** : Après 5 cartes tirées, le jeu s'arrête
- **Choix** : Chaque joueur peut parier 3 gorgées sur UN seul cheval
- **Gain** : Si le cheval gagne → distribue 3 gorgées
- **Perte** : Si le cheval perd → boit 6 gorgées (double)

### Stratégies avancées

**Stratégie Conservative** :
- Répartir 1-2 gorgées sur chaque cheval
- Assure de distribuer au moins quelques gorgées
- Faible risque, faible récompense

**Stratégie Aggressive** :
- Tout miser sur 1-2 chevaux
- Potentiel de grande distribution
- Risque élevé de ne rien distribuer

**Stratégie Bonus** :
- Économiser des gorgées pour le bonus
- Analyser les positions à 5 cartes
- Maximiser le retour sur investissement

---

## 📊 Statistiques et Suivi

Le jeu enregistre automatiquement :
- **Courses jouées** : Nombre total de courses
- **Victoires par cheval** : ♠️ ♥️ ♦️ ♣️
- **Taux de victoire** : Pourcentage par couleur

Ces statistiques permettent d'identifier :
- Les chevaux "chanceux" de la soirée
- Les tendances de jeu
- Les meilleures stratégies

---

## 🎓 Pour les Développeurs

### Architecture du code

**`app.js`** - Structure modulaire :
```javascript
// Game State (état global)
const gameState = {
    settings: {},      // Configuration
    players: [],       // Joueurs et paris
    horses: {},        // Positions des chevaux
    deck: [],          // Paquet de cartes
    stats: {}          // Statistiques
};

// Modules principaux
- Settings Functions  (configuration)
- Game Initialization (démarrage)
- Race Track Rendering (affichage piste)
- Betting System (système de paris)
- Game Logic (logique de jeu)
- Bonus System (gestion bonus)
- Winner Modal (résultats)
```

**`style.css`** - Organisation :
```css
/* Sections */
1. Reset & Base Styles
2. Header
3. Cards & Containers
4. Settings Panel
5. Buttons
6. Race Track
7. Betting Panel
8. Statistics
9. Modal
10. Footer
11. Responsive (mobile-first)
```

### Personnalisation

**Changer les couleurs** :
```css
:root {
    --primary: #2563eb;      /* Bleu principal */
    --success: #10b981;      /* Vert succès */
    --warning: #f59e0b;      /* Orange warning */
    --danger: #ef4444;       /* Rouge danger */
}
```

**Ajouter un cheval** :
```javascript
// Dans gameState.horses
joker: { name: '🃏 Joker', position: 0, color: 'purple' }

// Adapter le deck
gameState.deck.push('joker');
```

**Modifier les règles** :
```javascript
// Dans gameState.settings
defaultSips: 10,           // Gorgées par défaut
maxPlayers: 12,            // Joueurs max
bonusMultiplier: 3         // Multiplicateur bonus
```

---

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. **Fork** le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Committer les changements (`git commit -m 'Add AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une **Pull Request**

### Idées de contributions

- [ ] Mode multijoueur en ligne (WebSockets)
- [ ] Système de tournoi avec classement
- [ ] Sons et effets audio
- [ ] Thèmes visuels (dark mode, casino, etc.)
- [ ] PWA (Progressive Web App) pour installation mobile
- [ ] Historique des courses avec replay
- [ ] Variantes de règles supplémentaires
- [ ] Traduction multilingue

---

## 📄 Licence

Ce projet est sous licence **MIT** - voir [LICENSE](LICENSE) pour détails.

---

## 👤 Auteur

**Adam Beloucif**
- GitHub : [@Adam-Blf](https://github.com/Adam-Blf)
- LinkedIn : [Adam Beloucif](https://www.linkedin.com/in/adambeloucif/)
- Portfolio : [adambeloucif.com](https://adambeloucif.com)

---

## ⚠️ Avertissement

Ce jeu est conçu pour divertir et animer des soirées entre adultes majeurs. **Consommez avec modération**. L'abus d'alcool est dangereux pour la santé.

- 🚫 Ne pas conduire après avoir bu
- 🚫 Respecter les limites de chacun
- ✅ Boire de l'eau régulièrement
- ✅ Prévoir un moyen de transport sûr

---

## 🎉 Remerciements

Inspiré par les jeux de bar traditionnels et les soirées étudiantes. Merci à tous ceux qui font vivre ces moments de convivialité !

---

<div align="center">

**🏇 Fait avec ♠️ ♥️ ♦️ ♣️ et JavaScript**

⭐ **Star ce projet si tu l'aimes !** ⭐

[Signaler un bug](https://github.com/Adam-Blf/PMU-Game/issues) | [Demander une fonctionnalité](https://github.com/Adam-Blf/PMU-Game/issues)

</div>

---

*Dernière mise à jour : 20 novembre 2025*

---

<p align="center">
  <sub>Par <a href="https://adam.beloucif.com">Adam Beloucif</a> · Data Engineer & Fullstack Developer · <a href="https://github.com/Adam-Blf">GitHub</a> · <a href="https://www.linkedin.com/in/adambeloucif/">LinkedIn</a></sub>
</p>
