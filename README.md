<p align="center">
  <a href="https://github.com/librariums/StateURL-Studio/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
  <img src="https://img.shields.io/badge/Languages-FR%20%7C%20EN-purple.svg" alt="Languages FR | EN">
</p>

<p align="center">
  <strong><a href="https://librariums.github.io/StateURL-Studio/">Live Demo / Application en ligne</a></strong>
</p>

<p align="center">
  <a href="#version-française-fr">Version Française (FR)</a> │ 
  <a href="#english-version-en">English Version (EN)</a>
</p>

---

## Version Française (FR)

### Overview
StateURL Studio est un utilitaire web Privacy-First conçu pour compresser et sérialiser l'intégralité d'un état de configuration ou d'une note technique directement dans l'URL. L'URL agit comme la base de données. L'application fonctionne à 100% côté client, de manière autonome et décentralisée.

### Architecture & Privacy
- **Client-Side Only :** Aucune infrastructure serveur à maintenir, éliminant tout risque de fuite de données ou d'interception.
- **Zero-Friction :** Outil immédiatement opérationnel, sans inscription ni suivi utilisateur (tracking).
- **Data Sovereignty :** Conçu pour la manipulation de données sensibles (fichiers .env, configurations d'infrastructure, payloads d'API). Les données ne quittent pas l'environnement d'exécution du navigateur.
- **Sustainability :** Architecture Zero-Dependency écrite en pur JavaScript (Vanilla JS), HTML5 et CSS natif. Ne nécessite aucun processus de build (Node.js/npm).

### Technical Features
- **Compression Gzip :** Implémentation de l'API standard CompressionStream pour optimiser l'empreinte mémoire et respecter la limite de capacité universelle des URL (2 KB).
- **Synchronous Telemetry :** Analyse en temps réel (0 ms) de l'efficacité algorithmique et de la taille de l'état sans bloquer le thread principal.
- **Asynchronous Safety :** Mécanisme de verrouillage anti-collision (Race Condition) pour réguler les écritures dans l'historique du navigateur (history.replaceState).
- **Web Content Accessibility Guidelines (WCAG) :** Conformité aux standards d'accessibilité (Contrastes AAA, navigation sémantique, support prefers-reduced-motion, prefers-color-scheme).

### Usage
L'application est directement exploitable en ligne. Aucun clonage ni installation requise.
1. Accédez à l'application : [StateURL Studio](https://librariums.github.io/StateURL-Studio/)
2. Pour un auto-hébergement (Self-hosting) : téléchargez le fichier unique index.html et déployez-le sur l'infrastructure statique de votre choix (GitHub Pages, Vercel, S3).

---

## English Version (EN)

### Overview
StateURL Studio is a Privacy-First web utility designed to compress and serialize an entire configuration state or technical note directly into the URL. The URL acts as the data store. The application runs 100% client-side, fully standalone, and decentralized.

### Architecture & Privacy
- **Client-Side Only :** No server infrastructure to maintain, eliminating risks of data leaks or interception.
- **Zero-Friction :** Instantly operational tool with no signup process or user tracking.
- **Data Sovereignty :** Built for handling sensitive data (.env files, infrastructure configs, API payloads). Data never leaves the browser's execution environment.
- **Sustainability :** Zero-dependency architecture written in pure Vanilla JavaScript, HTML5, and native CSS. Requires no build process (Node.js/npm).

### Technical Features
- **Gzip Compression :** Implementation of the standard CompressionStream API to optimize footprint and comply with the universal URL capacity limit (2 KB).
- **Synchronous Telemetry :** Real-time analysis (0 ms) of algorithmic efficiency and state size without blocking the main thread.
- **Asynchronous Safety :** Race-condition locking mechanism to regulate browser history writes (history.replaceState).
- **Web Content Accessibility Guidelines (WCAG) :** Compliance with accessibility standards (AAA contrasts, semantic navigation, prefers-reduced-motion, prefers-color-scheme support).

### Usage
The application is fully operational online. No cloning or installation is required.
1. Access the application: [StateURL Studio](https://librariums.github.io/StateURL-Studio/)
2. For self-hosting: download the single index.html file and deploy it on the static infrastructure of your choice (GitHub Pages, Vercel, S3).
