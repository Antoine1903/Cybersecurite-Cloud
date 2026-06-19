# Sécurisation des communications réseau sur Kubernetes (Minikube)

## Objectif
Ce projet a pour but de mettre en pratique la sécurisation des flux réseau dans un cluster Kubernetes local, à travers la mise en place de NetworkPolicies basées sur une approche "deny-all".

## Contexte
Déploiement d’une application microservices de type e-commerce sur un cluster Minikube.

## Travail réalisé
- Déploiement d’une application microservices sur Kubernetes
- Mise en place d’une politique "deny-all" par défaut
- Création de règles NetworkPolicies pour autoriser uniquement les communications nécessaires
- Analyse des flux inter-services
- Application du principe du moindre privilège

## Compétences travaillées
- Kubernetes (NetworkPolicies)
- Sécurisation réseau applicative
- Isolation des workloads
- Analyse de flux inter-services
- Administration de cluster local (Minikube)

## Remarque
Projet réalisé dans un cadre d’apprentissage / étude des mécanismes de sécurité réseau sur Kubernetes.
