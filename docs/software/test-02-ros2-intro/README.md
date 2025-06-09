# Test 2 : Introduction à ROS2

## 🎯 Objectifs
- Comprendre l'architecture ROS2
- Créer des nœuds publisher et subscriber
- Implémenter une communication entre nœuds
- Utiliser les fichiers launch et les paramètres

## 📋 Spécifications Techniques

### Environnement
- ROS2 Humble
- Ubuntu 22.04 LTS
- Python 3.10+

### Requis
- Package ROS2 complet
- Communication Publisher/Subscriber
- Utilisation des topics et messages
- Configuration via launch files

## 🔧 Implémentation

### Structure du Package
```
my_robot_pkg/
├── launch/
├── src/
├── msg/
├── CMakeLists.txt
└── package.xml
```

### Composants
- Publisher Node : données des capteurs
- Subscriber Node : traitement des données
- Launch Files : configuration du système
- Messages personnalisés

## 📊 Grille d'Évaluation (100 points)

### Architecture ROS2 (25 points)
- Structure du package
- Organisation des nœuds
- Configuration des dépendances

### Communication (25 points)
- Publication des données
- Souscription aux topics
- Gestion des messages

### Launch Files (20 points)
- Configuration des nœuds
- Paramètres
- Réutilisabilité

### Documentation (20 points)
- README du package
- Documentation du code
- Diagrammes d'architecture

### Qualité du Code (10 points)
- Style Python/C++
- Bonnes pratiques ROS2
- Gestion des erreurs

## 📸 Média
- Captures rqt_graph
- Démonstrations des nœuds
- Visualisation des données

## 🔗 Ressources
- [Documentation officielle ROS2]
- [Tutoriels ROS2]
- [Exemples de packages]
- [Guide des messages]
