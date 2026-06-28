## Intégration et gestion Git 

Les branches feature/style et feature/contact ont été intégrées dans main.

### Processus utilisé :
1. Vérification de main
2. Fusion de feature/style
3. Fusion de feature/contact
4. Vérification finale de cohérence

### Gestion des conflits :
En cas de conflit Git :
- D'aborb on identifie les zones marquées par <<<<<<< ======= >>>>>>>
- Ensuite choisir ou fusionner les versions
- Puis supprimer les marqueurs
- ET enfin on effectue un commit de résolution

---

# Carte de visite personnelle

## Présentation
Page web personnelle avec présentation, bio, photo et formulaire de contact.

## Installation
1. Cloner le dépôt : `git clone https://github.com/ernestnatama8-beep/carte-visite.git`
2. Ouvrir `frontend/index.html` dans un navigateur

## Structure du projet
projet/
├── frontend/
│   ├── index.html
│   ├── contact.html
│   └── style.css
├── backend/
├── README.md
├── CHANGELOG.md
└── .gitignore

## Technologies utilisées
- HTML
- CSS
- Git