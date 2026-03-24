# FAROAD - Exercice Technique Backend

## Objectif

Connecter un point de charge et stocker les statuts de fonctionnement.

### Partie 1 : Le Code

**Mission :**
Conçois et implémente un serveur d'ingestion de données.

1. Le serveur doit exposer un point d'entrée **WebSocket** (WS).
2. Il doit recevoir et comprendre des requêtes **StatusNotification** du protocole **OCPP 1.6**.
3. Le serveur doit stocker les messages reçus pour en conserver une trace et un historique.

**Pour tester :**
Il existe plusieurs simulateurs OCPP open-source. Tu es totalement libre de chercher et d'utiliser celui de ton choix pour envoyer les payloads vers ton serveur et valider son fonctionnement.

**Contraintes techniques :**
* Stack imposée : **Node.js et TypeScript**.
* Pour tout le reste, **tu as carte blanche**.

---

### Partie 2 : System Design

Demain, FAROAD déploie **100 000 bornes connectées simultanément**.

Dans ton `README.md`, explique-nous :
Comment ferais-tu évoluer l'architecture pour tenir cette charge de messages WebSocket de manière fiable ?

---

## Livrables

Un lien vers ton dépôt Git (public ou privé partagé avec nous).

Nous organiserons un échange technique avec notre CTO à la réception de ton code.
