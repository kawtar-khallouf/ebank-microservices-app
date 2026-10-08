# 🏦 Activité Pratique : Implémentation d'un Service Bancaire avec Spring Boot, REST & GraphQL

## 🎯 Objectif du Projet
Ce projet s'inscrit dans le cadre de l'apprentissage des architectures logicielles modernes. Il consiste à développer un service robuste de gestion de comptes bancaires avec **Spring Boot**, intégrant la persistance des données, la gestion des DTOs, des mappers, ainsi que l'exposition d'**API REST** et **GraphQL**.

---

## 📋 Énoncé et Réalisations

1. **Initialisation** : Création du projet Spring Boot avec les dépendances Web, Spring Data JPA, H2 Database et Lombok.
2. **Modélisation** : Création des entités JPA `BankAccount` et `Customer`, ainsi que des énumérations (`AccountType`).
3. **Persistance (DAO)** : Mise en place de l'interface `BankAccountRepository` basée sur Spring Data JPA.
4. **Tests DAO** : Validation des opérations de persistance en base de données mémoire H2.
5. **API RESTful** : Développement des contrôleurs REST pour la gestion des comptes.
6. **Tests API** : Validation des endpoints via des clients REST (Postman).
7. **Documentation** : Intégration de Springdoc OpenAPI / Swagger UI pour documenter les API.
8. **Spring Data REST** : Exposition automatisée des repositories et utilisation de projections.
9. **Architecture Propre** : Implémentation des objets de transfert de données (**DTO**) et des **Mappers**.
10. **Logique Métier** : Structuration de la couche service (`AccountService` et `AccountServiceImpl`).
11. **API GraphQL** : Exposition d'un web service GraphQL pour des requêtes et mutations flexibles (inspiré des tutoriels du Pr. Mohamed Youssfi).

---

## 🛠️ Technologies & Stack Technique

- **Langage** : Java 21
- **Framework** : Spring Boot 3.x
- **Web & API** : Spring Web MVC, Spring Data REST, Spring for GraphQL
- **Persistance** : Spring Data JPA, H2 Database (In-Memory)
- **Utilitaires** : Lombok
- **Documentation** : Springdoc OpenAPI (Swagger UI)
- **Outil de Build** : Maven

---

## 🚀 Démarrage Rapide

### Prérequis
- Java 21 installé sur votre machine.

### Lancement de l'application
Placez-vous à la racine du projet dans votre terminal :

- **Sous Linux / macOS :**
  ```bash
  ./mvnw spring-boot:run