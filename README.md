# Projet Gestion de Salles

Application Java de gestion de salles (salles de réunion, salles de classe, etc.) avec **Hibernate**, **JPA** et **Maven**.

---

##  Objectif du projet

Ce projet permet de gérer un ensemble de salles et leurs réservations :
- Ajout, modification, suppression de salles
- Ajout , modification, supression des utilisateure
- Trouver une salle par disponibilité, et capacité minimal
- Trouver un utilisateure par son email

C’est un cas pratique classique pour appliquer les concepts ORM avec Hibernate/JPA dans un contexte métier concret (gestion de ressources partagées).

---

##  Technologies utilisées

- **Java** (JDK 17.0.15)
- **Maven** (gestion des dépendances)
- **Hibernate** (ORM)
- **JPA** 
- **H2** 

---

## Fonctionnalités principales

- Gestion des salles : nom, capacité, équipement, localisation...
- Création de réservation : date début/fin, utilisateur, salle choisie
- Vérification automatique des conflits de planning
- Affichage des réservations existantes
- Suppression / annulation de réservation
- Recherche : salles disponibles sur une période donnée

---

## Video Demo



https://github.com/user-attachments/assets/718c8dd5-a7bd-4e44-9e67-fc637fed5ca9

---

## Conclusion

Ce projet de gestion de salles est un excellent exercice pour maîtriser les relations JPA (OneToMany/ManyToOne entre Salle et Reservation), la gestion transactionnelle, et surtout la logique métier critique de vérification de disponibilité — un classique dans les systèmes de booking.
