# 🌐 Online IP Subnet Calculator

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

Un calculateur de sous-réseau IP en ligne, rapide, intuitif et responsive. Cet outil permet aux administrateurs réseau, ingénieurs cybersécurité et étudiants d'analyser instantanément une adresse IPv4 et son masque CIDR pour obtenir tous les paramètres réseau essentiels.

---

## ✨ Fonctionnalités

* 📡 **Calcul Réseau Complet :**
  * Adresse Réseau (*Network Address*)
  * Adresse de Diffusion (*Broadcast Address*)
  * Plage d'adresses hôtes utilisables (*First Host* - *Last Host*)
  * Masque de sous-réseau (*Subnet Mask*) & Masque inversé (*Wildcard Mask*)
  * Nombre total d'hôtes utilisables
* 🔍 **Analyse Avancée :**
  * Détection de la Classe IP (Classe A, B, C, D, E et Loopback)
  * Identification du Type d'IP (Publique vs Privée RFC 1918)
  * Conversion dynamique de l'adresse IP en format binaire (32 bits)
* ⚡ **Prise en charge des cas spécifiques :** Gestion correcte des masques `/31` (liaisons point-à-point RFC 3021) et `/32` (hôte unique).
* 🎨 **Interface Moderne :** Design responsive avec thème sombre (*Dark Mode*) adapté aux écrans mobiles et de bureau.
* 🚀 **Zéro dépendance :** Construit uniquement en Vanilla HTML, CSS et JavaScript.

---

## 🛠️ Stack Technique

* **HTML5** : Structure sémantique et éléments de formulaire.
* **CSS3** : Variables CSS, Grid Layout et design responsive sans framework.
* **JavaScript (ES6+)** : Manipulation de bits (*Bitwise operators*), validation REGEX et calculs d'adresses réseau.

---

## 🚀 Installation & Utilisation Locale

1. **Cloner le dépôt :**
   ```bash
   git clone [https://github.com/votre-utilisateur/ip-subnet-calculator.git](https://github.com/votre-utilisateur/ip-subnet-calculator.git)
