# Cahier des charges – Projet Automated Cyber Range

## Objectif général
Créer une plateforme de cyber range pour simuler des attaques et appliquer du machine learning à des fins de détection et de prédiction.

## Utilisateurs cibles
- Moi-même (apprentissage)
- Camarades ou professeurs (partage)
- Recruteurs (valorisation en entretien)

## Attaques simulées
- Brute-force SSH
- SQL Injection
- Cross-Site Scripting (XSS)
- Reverse Shell
- Path Traversal

## Outils techniques
- Docker pour l’environnement isolé
- Python, Bash pour l’automatisation des attaques
- Scikit-learn, pandas, matplotlib pour l’analyse ML
- tcpdump et journald pour la collecte de données

## Objectifs analytiques
- Prédire le prochain service ciblé (ML supervisé)
- Classer les attaques observées
- Détecter les anomalies réseau (ML non supervisé)

## Livrables
- Scripts d’attaque
- Environnement dockerisé
- Fichiers `.pcap` et logs
- Modèles ML et scripts d’analyse
- Documentation et rapport final
