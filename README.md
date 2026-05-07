# Choral-Riff
Application de gestion de partitions musicales
Description

Cette application permet de gérer des partitions musicales pour des ensembles (chorales, groupes, orchestres).

Elle facilite le partage et l’organisation de documents musicaux (partitions, fichiers audio, vidéos, etc.) entre les membres d’un ensemble.

Le projet répond à un besoin concret de chorale (≈ 60 membres répartis en 4 pupitres) afin de centraliser les documents et éviter les pertes de fichiers.

Objectif
Centraliser les partitions musicales
Faciliter le partage entre musiciens
Gérer les rôles et permissions des utilisateurs
Permettre l’accès aux documents par pupitre ou ensemble
Fonctionnalités

Utilisateurs
Inscription et connexion sécurisée
Gestion des rôles (ADMIN, MEMBER, OWNER)


Ensembles
Création d’un ensemble musical
Ajout et gestion de membres
Attribution de droits (chef de chœur / responsable)

Morceaux
Création de fiches morceaux
Ajout de partitions et médias
Association à des instruments ou pupitres

Documents
Upload de fichiers (PDF, image, audio)
Lecture des fichiers audio
Suppression selon les droits utilisateur

Stack technique
Backend : Spring Boot (Java)
Frontend : React
API REST
Base de données : PostgreSQL

Sécurité
Authentification par email/mot de passe
Mots de passe hashés
Gestion des rôles et permissions
Protection contre injections (SQL)

Installation
### Frontend (React + Vite)
cd frontend  
npm install  
npm run dev  

### Backend (Spring Boot)
cd backend  
./mvnw spring-boot:run  

### Dev Container
Ouvrir le projet dans VS Code → "Reopen in Container"  
Puis :

./mvnw spring-boot:run
