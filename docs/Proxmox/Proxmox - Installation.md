---
tags:
  - HTML5
  - JavaScript
  - CSS
---

# Guide d'Installation de Proxmox

Ce guide vous aidera à installer Proxmox sur votre serveur. Suivez les étapes ci-dessous pour une installation réussie.

## Prérequis

Avant de commencer l'installation, assurez-vous d'avoir les éléments suivants :
- Un serveur compatible avec Proxmox (64 bits, support de la virtualisation matérielle).
- Une connexion Internet stable.
- Un support d'installation (clé USB ou CD/DVD) avec l'image ISO de Proxmox.

## Étapes d'Installation

### 1. Téléchargement de l'ISO

1. Rendez-vous sur le [site officiel de Proxmox](https://www.proxmox.com/en/downloads) pour télécharger la dernière version de l'image ISO.
2. Choisissez l'option de téléchargement appropriée et enregistrez le fichier sur votre ordinateur.

### 2. Création du Support d'Installation

1. Utilisez un outil comme Rufus (pour Windows) ou Etcher (pour macOS/Linux) pour créer un support d'installation bootable à partir de l'image ISO.
2. Insérez votre clé USB ou CD/DVD dans votre ordinateur et suivez les instructions de l'outil pour créer le support.

### 3. Démarrage du Serveur

1. Insérez le support d'installation dans le serveur cible.
2. Démarrez le serveur et accédez au menu de démarrage (généralement en appuyant sur F2, F10, F12 ou Échap).
3. Sélectionnez le support d'installation comme périphérique de démarrage.

### 4. Installation de Proxmox

1. Une fois le serveur démarré sur le support d'installation, suivez les instructions à l'écran pour installer Proxmox.
2. Acceptez les termes de la licence et sélectionnez le disque dur sur lequel vous souhaitez installer Proxmox.
3. Configurez le réseau en entrant les informations IP appropriées.
4. Définissez un mot de passe pour l'utilisateur root et entrez une adresse e-mail pour les notifications système.

### 5. Finalisation de l'Installation

1. Une fois l'installation terminée, retirez le support d'installation et redémarrez le serveur.
2. Accédez à l'interface web de Proxmox en entrant l'adresse IP du serveur dans un navigateur web (par exemple, https://votre-ip:8006).
3. Connectez-vous avec l'utilisateur root et le mot de passe que vous avez défini.

## Configuration Post-Installation

- **Mises à jour** : Assurez-vous que votre installation de Proxmox est à jour en exécutant les commandes de mise à jour.
- **Sauvegardes** : Configurez un plan de sauvegarde régulier pour vos machines virtuelles.
- **Sécurité** : Activez les pare-feu et configurez les règles de sécurité nécessaires pour protéger votre serveur.

Félicitations, vous avez installé Proxmox avec succès ! Vous pouvez maintenant commencer à créer et gérer vos machines virtuelles et conteneurs.

