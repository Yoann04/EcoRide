# EcoRide – Application web de covoiturage écologique

## 📖 Présentation

EcoRide est une application web de covoiturage développée dans le cadre de l’évaluation
**ECF – Développeur Web et Web Mobile** de Studi.  
Le projet permet la mise en relation de **conducteurs** et **passagers** souhaitant partager un trajet de manière simple, sécurisée et écologique.

L’objectif est de promouvoir la **mobilité durable** à travers une interface moderne, intuitive et responsive.

## Technologies utilisées

### Frontend :

- Angular 18
- TypeScript
- HTML / SCSS (responsive)
- Figma (maquettes et prototype)

### Backend :

- Symfony 7.1 (PHP 8.2)
- Doctrine ORM
- LexikJWTAuthenticationBundle (authentification JWT)
- MySQL (base relationnelle)
- MongoDB (prévu pour les futures statistiques)

### Outils :

- VS Code
- Postman (tests API)
- Git / GitHub
- QuickBDD (modélisation de la base de données)

## Installation et lancement du projet

### Prérequis

Assurez-vous d’avoir installé :

- PHP ≥ 8.2
- Composer
- Symfony CLI
- Node.js ≥ 18
- Angular CLI
- MySQL

### Clonage du projet

```bash
git clone https://github.com/Yoann04/ecoride.git
cd ecoride
```

---

## Gestion du versionnement (Git)

Le projet EcoRide suit une organisation Git structurée :

- **main** → branche stable contenant les versions validées.
- **dev** → branche de développement pour les fonctionnalités en cours.
- **feature/** → branches spécifiques pour chaque nouvelle fonctionnalité (ex : `feature/authentication`).

### Commandes principales

```bash
# Création d’une branche de développement
git checkout -b dev

# Création d’une branche de fonctionnalité
git checkout -b feature/authentication

# Validation et fusion
git add .
git commit -m "Ajout fonctionnalité d'authentification"
git push -u origin feature/authentication

# Fusion vers la branche dev
git checkout dev
git merge feature/authentication
git push
```

Ajout d’une branche de développement (dev) pour structurer le workflow Git.
