# Cahier des Charges - ZoomFiT
**Projet interne - Techniques de l'informatique 420.B0**  
**Période :  octobre -  décembre 2025**

---

## 1. Informations Générales du Projet

**Nom du projet :** FitTracker  
**Type d'application :** Application web full-stack  
**Domaine :** Suivi fitness et nutrition personnel  
**Formation :** Techniques de l'informatique 420.B0 - Institut Teccart  
**Étudiant :** Ariss Benabbas  
**Période de réalisation :** 9 semaines (1 oct - 5 déc 2025)

---

## 2. Contexte et Justification

Avec l'augmentation de l'intérêt pour la santé et le fitness, de nombreuses personnes cherchent des outils simples pour suivre leurs activités physiques et leur alimentation. Les solutions existantes sont souvent complexes ou payantes.

**Problématiques identifiées :**
- Manque d'outils simples et gratuits pour le suivi personnel
- Difficulté à maintenir la motivation sans coach
- Absence de vue d'ensemble sur les progrès
- Interfaces souvent complexes pour les débutants

**Solution proposée :**
FitTracker est une application web intuitive permettant aux utilisateurs de suivre leurs entraînements, leur nutrition et leurs progrès de manière simple et motivante.

---

## 3. Objectifs de l'Application

### Objectifs principaux :
- Créer un système de suivi d'entraînements personnalisé
- Développer un tracker nutritionnel simple et efficace
- Offrir un tableau de bord visuel des progrès
- Implémenter un système de motivation par objectifs

### Objectifs pédagogiques :
- Appliquer les compétences en développement full-stack
- Utiliser React pour une interface moderne
- Implémenter Node.js et Express.js côté serveur
- Gérer une base de données MongoDB
- Appliquer les bonnes pratiques de sécurité web

---

## 4. Description Fonctionnelle

### 4.1 Modules principaux

**Module Authentification :**
- Inscription/connexion sécurisée
- Gestion des sessions utilisateur
- Protection des routes privées

**Module Profil Utilisateur :**
- Informations personnelles (âge, poids, taille, objectifs)
- Paramètres de l'application
- Historique d'activité

**Module Entraînement :**
- Création et gestion d'exercices personnalisés
- Suivi des séances d'entraînement
- Historique des performances
- Calcul de statistiques simples (progression, fréquence)

**Module Nutrition :**
- Journal alimentaire quotidien
- Base de données d'aliments de base
- Calcul des calories et macronutriments
- Suivi des objectifs nutritionnels

**Module Tableau de Bord :**
- Vue d'ensemble des activités récentes
- Graphiques de progression simples
- Rappels et objectifs
- Statistiques personnelles

**Module Administration (Basique) :**
- Gestion des utilisateurs
- Gestion de la base de données d'aliments
- Statistiques globales d'utilisation

### 4.2 Fonctionnalités détaillées

**Suivi d'Entraînement :**
- Ajout d'exercices avec séries, répétitions, poids
- Timer intégré pour les temps de repos
- Historique des séances par date
- Calcul du volume d'entraînement total

**Tracker Nutrition :**
- Recherche d'aliments dans la base de données
- Ajout rapide de repas récurrents
- Calcul automatique des totaux quotidiens
- Comparaison avec les objectifs fixés

**Visualisation des Données :**
- Graphiques de progression du poids
- Évolution du volume d'entraînement
- Tendances nutritionnelles
- Calendrier d'activité

---

## 5. Spécifications Techniques

### 5.1 Stack technologique (basé sur vos compétences)

**Frontend :**
- **Framework :** React avec JavaScript
- **Styling :** CSS3 + Bootstrap pour le responsive
- **Gestion d'état :** React Hooks (useState, useEffect)
- **Routing :** React Router
- **Charts :** Chart.js ou bibliothèque similaire simple

**Backend :**
- **Runtime :** Node.js
- **Framework :** Express.js
- **Authentification :** JWT (JSON Web Tokens)
- **Middleware :** CORS, body-parser, express-session

**Base de données :**
- **Base principale :** MongoDB avec Mongoose
- **Structure :** Collections pour Users, Workouts, Foods, Meals

**Outils de développement :**
- **IDE :** VS Code
- **Version Control :** Git + GitHub
- **Testing :** Postman pour les APIs
- **Déploiement :** Local avec possibilité d'hébergement simple

### 5.2 Architecture de l'application

**Architecture :** Modèle MVC traditionnel  
**API :** RESTful avec Express.js  
**Authentification :** Sessions + JWT  
**Sécurité :** Validation des inputs, protection CSRF basique

---

## 6. Utilisateurs Cibles

### Utilisateur principal :
**Personas :** Débutants en fitness souhaitant un outil simple pour commencer à suivre leurs activités et leur alimentation

**Besoins identifiés :**
- Interface simple et intuitive
- Fonctionnalités de base sans complexité
- Motivation par visualisation des progrès
- Accès rapide aux informations essentielles

---

## 7. Livrables Attendus

### 7.1 Application fonctionnelle
- **Application web** complète et fonctionnelle
- **Base de données** peuplée avec données de test
- **API REST** documentée avec Postman
- **Interface utilisateur** responsive et moderne

### 7.2 Documentation
- **Code source** commenté et structuré
- **README** avec instructions d'installation
- **Documentation API** avec exemples
- **Guide utilisateur** basique

### 7.3 Rapports hebdomadaires
- **Rapport hebdomadaire** chaque dimanche (format fourni)
- **Rapport final** selon le gabarit fourni
- **Présentation** pour la soutenance du 16 décembre

---

## 8. Planning de Réalisation (9 semaines)

### **Semaine 1 (1-6 octobre) : Conception et Setup**
- Finalisation du cahier des charges
- Setup de l'environnement de développement
- Configuration Git et structure de projet
- Création des maquettes de base (wireframes)
- **Livrable :** Projet initialisé + maquettes

### **Semaine 2 (7-13 octobre) : Base de données et Backend**
- Modélisation de la base de données MongoDB
- Setup Express.js et configuration de base
- Implémentation des modèles Mongoose
- Création des routes d'authentification
- **Livrable :** Backend de base + authentification

### **Semaine 3 (14-20 octobre) : APIs Principales**
- Développement des APIs utilisateur
- Implémentation des CRUD pour les entraînements
- Création des APIs nutrition de base
- Tests des endpoints avec Postman
- **Livrable :** APIs principales fonctionnelles

### **Semaine 4 (21-27 octobre) : Frontend - Structure**
- Setup du projet React
- Configuration du routing
- Création des composants de base
- Implémentation de l'authentification frontend
- **Livrable :** Structure React + login/register

### **Semaine 5 (28 oct - 3 nov) : Interfaces Principales**
- Développement du tableau de bord
- Interface de gestion des entraînements
- Formulaires d'ajout/modification
- **Livrable :** Interfaces principales fonctionnelles

### **Semaine 6 (4-10 novembre) : Module Nutrition**
- Interface du journal alimentaire
- Recherche et ajout d'aliments
- Calculs nutritionnels
- **Livrable :** Module nutrition complet

### **Semaine 7 (11-17 novembre) : Visualisation et Polish**
- Intégration des graphiques (Chart.js)
- Amélioration de l'UX/UI
- Responsive design avec Bootstrap
- **Livrable :** Application avec visualisations

### **Semaine 8 (18-24 novembre) : Tests et Optimisations**
- Tests complets de l'application
- Corrections de bugs
- Optimisations de performance
- **Livrable :** Application stable et testée

### **Semaine 9 (25 nov - 1 déc) : Finalisation et Documentation**
- Documentation complète
- Préparation des données de démonstration
- Finalisation du rapport
- **Livrable :** Projet final complet

### **Semaine de présentation (2-8 décembre)**
- Remise du rapport (8 décembre)
- Préparation de la soutenance
- **Soutenance :** 16 décembre

---

## 9. Fonctionnalités Détaillées par Module

### Module Authentification
- Page d'inscription avec validation des champs
- Page de connexion avec gestion d'erreurs
- Déconnexion sécurisée
- Protection des routes privées

### Module Profil
- Formulaire d'informations personnelles
- Calcul automatique du BMR (métabolisme de base)
- Définition d'objectifs (poids cible, calories cibles)
- Historique des mesures corporelles

### Module Entraînement
- Liste des exercices disponibles (base de données simple)
- Création de séances d'entraînement
- Enregistrement des performances (poids, répétitions)
- Historique des séances avec recherche par date
- Statistiques de progression par exercice

### Module Nutrition
- Base de données d'aliments de base (100-200 items)
- Ajout rapide de repas avec portions
- Calcul des totaux quotidiens (calories, protéines, glucides, lipides)
- Comparaison avec les objectifs
- Historique nutritionnel par jour

### Module Dashboard
- Résumé de la semaine (entraînements, nutrition)
- Graphique de progression du poids (Chart.js)
- Graphique du volume d'entraînement hebdomadaire
- Objectifs de la semaine et progression

---

## 10. Base de Données - Structure Simplifiée

### Collection Users
```javascript
{
  _id: ObjectId,
  username: String,
  email: String,
  password: String (hashed),
  profile: {
    age: Number,
    weight: Number,
    height: Number,
    goal_weight: Number,
    daily_calories: Number,
    activity_level: String
  },
  created_at: Date
}
```

### Collection Workouts
```javascript
{
  _id: ObjectId,
  user_id: ObjectId,
  date: Date,
  exercises: [{
    name: String,
    sets: [{
      reps: Number,
      weight: Number,
      rest: Number
    }]
  }],
  total_duration: Number,
  notes: String
}
```

### Collection Foods
```javascript
{
  _id: ObjectId,
  name: String,
  calories_per_100g: Number,
  protein: Number,
  carbs: Number,
  fat: Number,
  category: String
}
```

### Collection Meals
```javascript
{
  _id: ObjectId,
  user_id: ObjectId,
  date: Date,
  meal_type: String, // breakfast, lunch, dinner, snack
  foods: [{
    food_id: ObjectId,
    quantity: Number // in grams
  }],
  total_calories: Number
}
```

---

## 11. Sécurité et Bonnes Pratiques

### Sécurité de base :
- Hashage des mots de passe avec bcrypt
- Validation des inputs côté serveur
- Protection contre les injections NoSQL
- CORS configuré correctement
- Sessions sécurisées

### Bonnes pratiques :
- Code commenté et organisé
- Gestion d'erreurs appropriée
- Messages d'erreur informatifs pour l'utilisateur
- Validation des données côté client et serveur
- Structure MVC respectée

---

## 12. Critères de Réussite

### Fonctionnels :
- Authentification complète et sécurisée
- CRUD complet pour entraînements et nutrition
- Visualisations graphiques fonctionnelles
- Interface utilisateur intuitive et responsive

### Techniques :
- Code propre et bien structuré
- API REST fonctionnelle et documentée
- Base de données correctement modélisée
- Application déployable localement

### Pédagogiques :
- Utilisation appropriée des technologies étudiées
- Respect des bonnes pratiques de développement
- Documentation complète et claire
- Présentation professionnelle

---

## 13. Gestion des Risques

### Risques identifiés :
1. **Complexité des graphiques** - Solution : Utiliser Chart.js avec des exemples simples
2. **Problèmes de déploiement** - Solution : Tester régulièrement en local
3. **Retard sur planning** - Solution : Prioriser les fonctionnalités core
4. **Difficultés techniques** - Solution : Utiliser les ressources du cours et l'aide des enseignants

### Plan de contingence :
- Réduire les fonctionnalités avancées si nécessaire
- Se concentrer sur un MVP (Minimum Viable Product) solide
- Documenter les difficultés rencontrées pour la présentation

---

## 14. Ressources Nécessaires

### Logiciels :
- VS Code 
- Node.js et npm
- MongoDB Community Server
- Git
- Navigateurs web pour tests

### Ressources d'apprentissage :
- Documentation React officielle
- Documentation MongoDB
- Tutoriels Chart.js
- Stack Overflow pour résolution de problèmes

---

## Conclusion

Ce projet FitTracker représente une excellente opportunité d'appliquer concrètement toutes les compétences acquises durant votre formation. Il est conçu pour être réalisable dans les 9 semaines imparties tout en offrant suffisamment de défis techniques pour démontrer votre maîtrise du développement full-stack.

L'application finale sera un produit complet et fonctionnel qui pourra figurer dans votre portfolio professionnel et démontrer vos compétences aux futurs employeurs.

---

**Date :** Octobre 2025  
**Étudiant :** Ariss Benabbas  
**Formation :** Techniques de l'informatique 420.B0 - Institut Teccart
