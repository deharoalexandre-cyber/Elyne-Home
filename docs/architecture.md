# Architecture — Elyne Home

[English](architecture.en.md) · [Présentation](../README.md)

## Flux simplifié

Voix ou événement local → interprétation → politique d'action → adaptateur domestique → retour et trace.

## Composants et frontières

- Le prototype local sépare écoute et synthèse vocales, mémoire, planification, client de modèle et adaptateurs IoT.
- Le site décrit un mini-serveur local, des caméras sur réseau isolé et des passerelles domotiques. Ce sont des contraintes de déploiement à réaliser et à vérifier, pas une garantie universelle du POC.
- Une action proactive doit rester gouvernée par un choix explicite de l'utilisateur et par les permissions de l'adaptateur concerné.

Ce schéma textuel décrit l'architecture du produit. Il ne remplace pas une vérification sur un build, un matériel et une configuration précis. Les [éléments de preuve](evidence.md) indiquent ce qui a été effectivement documenté.
