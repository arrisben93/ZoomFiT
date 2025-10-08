# Maquettes Wireframes - FitTracker
**Application de Suivi Fitness et Nutrition**

---

## Vue d'Ensemble des Wireframes

Ces wireframes définissent la structure et la disposition des éléments pour chaque page principale de l'application FitTracker. Ils servent de guide pour le développement de l'interface utilisateur en React avec Bootstrap.

---

## 1. Structure de Navigation

### Navigation Mobile
- **Bottom Navigation** : 4 onglets principaux
  - Dashboard (Accueil)
  - Entraînement
  - Nutrition
  - Profil

### Navigation Desktop  
- **Sidebar Navigation** : Menu latéral fixe
  - Dashboard
  - Entraînements
  - Nutrition
  - Profil
  - Historique
  - Déconnexion

---

## 2. Pages d'Authentification

### Page de Connexion
**Éléments principaux :**
- Logo FitTracker centré
- Champ Email
- Champ Mot de passe
- Bouton "Se connecter"
- Lien "S'inscrire"
- Lien "Mot de passe oublié"

**Responsive :**
- Mobile : Layout vertical centré
- Desktop : Centré avec largeur fixe

### Page d'Inscription
**Éléments similaires + :**
- Champ Nom d'utilisateur
- Champ Confirmation mot de passe
- Checkbox Conditions d'utilisation
- Bouton "S'inscrire"
- Lien "Déjà inscrit ? Se connecter"

---

## 3. Dashboard Principal

### Vue Mobile
**Header :**
- Salutation personnalisée
- Avatar utilisateur
- Icône notifications

**Contenu principal :**
- **Cards de statistiques :**
  - Poids actuel
  - Entraînements cette semaine
  - Calories aujourd'hui
  - Objectif de la semaine

**Graphiques :**
- Graphique progression poids (Chart.js)
- Graphique activité hebdomadaire

**Actions rapides :**
- Bouton "Nouvel entraînement"
- Bouton "Ajouter repas"

**Navigation :**
- Bottom navigation fixe

### Vue Desktop
**Layout :**
- Sidebar navigation gauche
- Contenu principal plus large
- Graphiques côte à côte
- Plus d'informations visibles

---

## 4. Module Entraînement

### Page Nouvel Entraînement
**Éléments principaux :**
- **Header avec timer**
- **Section ajout d'exercice :**
  - Dropdown sélection exercice
  - Champs Séries/Répétitions/Poids
  - Bouton "Ajouter série"
  - Bouton "Ajouter exercice"

**Liste des exercices ajoutés :**
- Nom de l'exercice
- Séries effectuées
- Option supprimer

**Footer :**
- Bouton "Terminer l'entraînement"
- Bouton "Annuler"

### Page Historique Entraînements
**Éléments :**
- Barre de recherche
- Filtres par date
- Liste des entraînements :
  - Date
  - Durée
  - Exercices (aperçu)
  - Bouton détails

---

## 5. Module Nutrition

### Page Journal Alimentaire
**Section recherche :**
- Barre de recherche d'aliments
- Filtre par catégorie
- Résultats de recherche

**Section repas :**
- Onglets : Petit-déjeuner, Déjeuner, Dîner, Collations
- Liste des aliments ajoutés avec quantités
- Bouton "Ajouter aliment"

**Résumé quotidien :**
- Calories totales vs objectif
- Barres de progression macros :
  - Protéines
  - Glucides
  - Lipides

**Actions :**
- Bouton "Sauvegarder la journée"

---

## 6. Module Profil

### Page Profil Utilisateur
**Informations personnelles :**
- Photo de profil (upload)
- Nom d'utilisateur
- Email
- Âge
- Sexe

**Informations physiques :**
- Poids actuel
- Taille
- Niveau d'activité

**Objectifs :**
- Objectif de poids
- Calories quotidiennes cibles
- Objectif d'entraînements/semaine

**Paramètres :**
- Unités (kg/lbs, cm/inches)
- Notifications
- Confidentialité

**Actions :**
- Bouton "Sauvegarder"
- Bouton "Changer mot de passe"

---

## 7. Composants Réutilisables

### Cards de Statistiques
**Structure :**
- Icône représentative
- Valeur principale (grande)
- Label descriptif
- Variation/tendance (optionnel)

### Formulaires
**Éléments standards :**
- Labels clairs
- Champs avec validation visuelle
- Messages d'erreur
- Boutons d'action cohérents

### Navigation
**Bottom Navigation Mobile :**
- 4 icônes avec labels
- Indicateur de page active
- Badges de notification

**Sidebar Desktop :**
- Logo en haut
- Menu items avec icônes
- Indicateur de page active
- Section utilisateur en bas

---

## 8. États et Interactions

### États de Chargement
- Spinners pour les données
- Skeleton screens pour les listes
- Messages de chargement

### États Vides
- Messages informatifs
- Boutons d'action suggérés
- Illustrations simples

### États d'Erreur
- Messages clairs
- Boutons de retry
- Suggestions d'action

---

## 9. Responsive Design

### Points de Rupture Bootstrap
- **Mobile :** < 768px
- **Tablet :** 768px - 991px  
- **Desktop :** > 992px

### Adaptations Mobile
- Navigation bottom fixe
- Cards empilées verticalement
- Formulaires pleine largeur
- Graphiques adaptés tactile

### Adaptations Desktop
- Sidebar navigation
- Layout en colonnes
- Graphiques plus larges
- Tableaux détaillés

---

## 10. Palette de Couleurs

### Couleurs Principales
- **Primary :** #007bff (Bleu Bootstrap)
- **Success :** #28a745 (Vert - Objectifs atteints)
- **Warning :** #ffc107 (Jaune - Attention)
- **Danger :** #dc3545 (Rouge - Erreurs)

### Couleurs Neutres
- **Dark :** #343a40 (Texte principal)
- **Light :** #f8f9fa (Arrière-plans)
- **Gray :** #6c757d (Texte secondaire)

### Utilisation
- Headers et navigation : Primary
- Boutons d'action : Success
- Alertes : Warning/Danger selon contexte
- Texte : Dark/Gray selon hiérarchie

---

## 11. Typographie

### Polices
- **Principale :** System fonts (Bootstrap default)
- **Fallback :** Arial, sans-serif

### Hiérarchie
- **H1 :** Titres de pages
- **H2 :** Sections principales
- **H3 :** Sous-sections
- **Body :** Texte courant
- **Small :** Informations secondaires

---

## 12. Icônes

### Bibliothèque
- **Bootstrap Icons** ou **Font Awesome**
- Cohérence dans le style
- Taille adaptée au contexte

### Utilisation
- Navigation : Icônes + texte
- Boutons : Icônes optionnelles
- États : Icônes de statut
- Actions : Icônes d'action

---

## Conclusion

Ces wireframes fournissent une base solide pour le développement de l'interface utilisateur FitTracker. Ils respectent les conventions Bootstrap tout en offrant une expérience utilisateur intuitive et cohérente sur tous les appareils.

**Prochaines étapes :**
1. Validation des wireframes
2. Création des composants React de base
3. Implémentation progressive avec Bootstrap
4. Tests utilisateurs sur les prototypes

---

**Note :** Ces wireframes sont conçus pour être simples à implémenter avec vos compétences actuelles en React et Bootstrap, tout en offrant une expérience utilisateur moderne et professionnelle.