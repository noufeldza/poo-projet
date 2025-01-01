# Rapport : Gestion des Dossiers Médicaux et Rendez-vous

## 1. Introduction

### Présentation du problème :

La gestion des dossiers médicaux et des rendez-vous dans les cliniques et cabinets médicaux est souvent archaïque, reposant sur des systèmes papiers ou des solutions numériques dispersées. Cela entraîne des inefficacités, des pertes de temps et une expérience utilisateur sous-optimale.

### Objectif principal :

Développer une solution numérique centralisée permettant de gérer efficacement les dossiers médicaux, les rendez-vous, et les documents médicaux tout en offrant une interface conviviale et accessible.

### Avantages :

- Gain de temps pour les professionnels de santé.
- Amélioration de l’expérience patient.
- Réduction des erreurs humaines.
- Centralisation et sécurisation des données.

## 2. Analyse des Besoins

### 2.1 Besoins Fonctionnels

- Gestion des dossiers médicaux : Création, modification, et consultation.
- Gestion des rendez-vous : Planification, modification, et annulation.
- Gestion des fiches patients : Informations personnelles et historiques médicaux.
- Génération automatique des certificats médicaux et ordonnances.

### 2.2 Besoins Non Fonctionnels

- Interface utilisateur intuitive et ergonomique.

- Sécurisation des données conformément aux régulations en vigueur.

## 3. Conception

- **Cas d’utilisation :** Description des fonctionnalités pour chaque profil utilisateur (administrateur, médecin, patient).
- **Classes :** Détails des entités principales et leurs relations (par ex., Patient, Rendez-vous, Document).

## 4. Développement

### Technologies utilisées :

- java.
- javax.swing (pour ui).

## 5. Fonctionnalités

### 5.1 Gestion des Dossiers Médicaux (Secrétaire)

- Création, modification, et suppression des dossiers.
- exemple test:<br><br>

 \-**Après l’exécution du programme :** se connecter avec le Compte de Secrétaire

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20162808.png)<br><br>
 \-**appuyer sur le bouton** ajouter un patient

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20183930.png)<br><br>
 \-**l'interface de manipulation des patients** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20163005.png)<br><br>
 \-**remplir les informations du patient** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20163810.png)<br><br>
 \-**après avoir ajouté plusieurs patients** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20163919.png)<br><br>
 \-**la recherche d'un patient** (le nom et le prenom)

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20163936.png)<br><br>
 \-**apres la recherche** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20164236.png)<br><br>
 \-**on modifier les informations du patient** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20164236.png)<br><br>
 \-**apres la modification** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20164246.png)<br><br>
 \-**on supprimé le patient 3** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20164026.png)<br><br>
 \-**après la suppression** 


   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20164558.png)<br><br>

### 5.2 Génération de Documents

- Ordonnances personnalisées.
- Certificats médicaux selon les normes.
- Fiches contenant les informations personnelles.
- Accès aux historiques médicaux et consultations.
- exemple test:<br><br>
 \-**se connecter avec le Compte de médecin** 


   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20164350.png)<br><br>
 \-**se connecter avec le Compte de médecin** 


   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20164350.png)<br><br>
 \-**l'interface du stafe medical** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20164625.png)<br><br>
 \-**remplir consultation** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20164828.png)<br><br>
 \-**remplir l'ordonnance** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20165127.png)<br><br>
 \-**l'historique de patient** 

   ![image](https://github.com/noufeldza/poo-projet/blob/main/pngs/Screenshot%202025-01-01%20165629.png)<br><br>
### 5.4 Gestion des Rendez-vous

- Saisie et gestion des rendez-vous via une interface intuitive.

## 6. Conclusion et Perspectives

### Résumé des bénéfices apportés par le logiciel :

- Amélioration de la gestion quotidienne des tâches administratives et médicales.
- Satisfaction accrue des utilisateurs grâce à une solution intuitive et efficace.

### Améliorations futures possibles :

- **Intégration avec des systèmes tiers :** Connexion avec des laboratoires d’analyses ou des pharmacies pour un échange simplifié des données.
- **Fonctionnalités de télémédecine :** Consultation à distance via des appels vidéo ou des chats sécurisés.
- **Analyse prédictive :** Utilisation de l’IA pour anticiper les besoins des patients et fournir des recommandations personnalisées.
- **Personnalisation accrue :** Adaptation des fonctionnalités en fonction des spécificités des cabinets ou des cliniques.
- **Support multilingue :** Mise à disposition d’une interface multilingue pour étendre l’utilisation à l’international.

