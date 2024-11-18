# HypoliaCore

**HypoliaCore** est un framework modulaire et extensible pour les plugins Minecraft. Il simplifie le développement de plugins en offrant des outils réutilisables, des utilitaires, et des fonctionnalités de base communes afin que les développeurs puissent se concentrer sur la création de fonctionnalités uniques pour leurs plugins.

## 🚀 Fonctionnalités

- **API simplifiée** pour interagir avec le serveur Minecraft.
- **Système d'événements** pour faciliter l'écoute d'événements globaux.
- **Utilitaires** pour la gestion des items, des messages, des fichiers de configuration, etc.
- **Modularité** : les fonctionnalités sont organisées en modules réutilisables.
- **Support des commandes** avec un système d'enregistrement simplifié.
- **Gestion centralisée des configurations** pour une personnalisation facile.

## 📂 Structure du projet

```text
hypolia.hypoliacore
├── core           # Classes de base pour le core du framework
├── utils          # Utilitaires communs (formatage, gestion de fichiers, etc.)
├── listeners      # Gestionnaires d'événements globaux
├── commands       # Commandes par défaut ou partagées
├── api            # Classes d'API publiques pour les plugins
├── modules        # Fonctionnalités modulaires réutilisables
└── config         # Gestion de la configuration

```