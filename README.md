# EquiHub

> Application mobile de gestion d'écurie conçue pour simplifier l'organisation quotidienne et centraliser les informations importantes.

## Présentation

**EquiHub** est une application destinée aux écuries.

Elle permet de regrouper au même endroit :

- les informations des chevaux ;
- les tâches quotidiennes ;
- les tâches hebdomadaires ;
- les alertes et le cahier de transmission ;
- les informations liées au suivi des chevaux ;
- les comptes et les accès des utilisateurs.

L'objectif est simple : **faciliter la communication et l'organisation au sein de l'écurie.**

---

## Fonctionnalités

### Chevaux

Chaque cheval dispose de sa propre fiche permettant notamment de retrouver :

- son nom ;
- son sexe ;
- sa date de naissance ;
- sa race ;
- sa robe ;
- son propriétaire ;
- son box ;
- son paddock ;
- les informations de santé ;
- les traitements ;
- le vétérinaire ;
- la maréchalerie ;
- les notes et consignes ;
- sa photo.

### Planning quotidien

Le planning permet de visualiser rapidement les tâches à effectuer au cours de la journée.

Les tâches sont organisées par moment :

- Matin
- Journée
- Soir

La progression de la journée permet de voir rapidement ce qui a déjà été réalisé.

### Tâches hebdomadaires

EquiHub permet également de gérer des tâches récurrentes sur plusieurs jours de la semaine.

Il est notamment possible de créer des tâches permanentes qui se répètent sans date de fin.

### Alertes

Le cahier de transmission permet de signaler une anomalie ou une information importante concernant un cheval ou un secteur de l'écurie.

Une alerte peut notamment contenir :

- le cheval ou secteur concerné ;
- le type d'anomalie ;
- une observation ;
- l'action réalisée ;
- un rappel horaire.

### Comptes utilisateurs

Les membres de l'écurie utilisent leur propre compte afin d'accéder aux données de l'application.

Les actions disponibles peuvent dépendre des droits de l'utilisateur.

---

## Technologies

EquiHub utilise notamment :

- **HTML**
- **CSS**
- **JavaScript**
- **Vite**
- **Capacitor**
- **Android Studio**
- **Supabase**

### Plateformes

| Plateforme | État |
|---|---|
| Android | Disponible |
| iOS | À venir |

---
## Pourquoi iOS n'est pas encore disponible ?

La version iOS d'EquiHub n'est pas encore distribuable.

Le développement de l'application est réalisé avec **Capacitor**, ce qui permet de créer une version Android et une version iOS à partir du même projet.

Cependant, la génération et la signature d'une application iOS nécessitent un environnement **macOS avec Xcode**. Apple impose également la signature de l'application avec les outils et certificats Apple nécessaires à sa distribution.

Actuellement, le développement d'EquiHub est effectué sur **Windows**. Il n'est donc pas possible de générer et signer correctement l'IPA destinée aux appareils iOS depuis cet environnement.

### Android

La version Android peut être générée et signée directement depuis Windows avec Android Studio.

### iOS

La version iOS pourra être préparée dès qu'un **Mac** sera disponible pour :

- ouvrir le projet iOS avec Xcode ;
- configurer la signature Apple ;
- générer l'application iOS ;
- tester l'application sur iPhone ;
- préparer sa distribution.

**La version iOS est donc prévue, mais actuellement en attente d'un environnement macOS.**

## Installation

### Android

La version Android est distribuée sous forme d'APK.

La dernière version est disponible dans les **Releases GitHub** du projet.

**Dernière version :**

[EquiHub — Releases](https://github.com/Noctrya72/EquiHub/releases/latest)
