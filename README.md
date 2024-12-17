# Mise-en-place-d-un-SOC

Projet : Mise en Place d’un SOC (Security Operations Center)
​
1. Contexte et Objectif

Ce projet a été réalisé dans le cadre de la mise en place d’un Security Operations Center (SOC) pour renforcer la sécurité informatique d’une entreprise face aux cybermenaces croissantes.

- Objectifs :

    Créer un environnement sécurisé et centralisé pour détecter, analyser, et répondre aux incidents de sécurité en temps réel.

    Intégrer des solutions techniques adaptées (SIEM, SOAR, EDR, IPS/IDS) pour optimiser la détection et la gestion des menaces.

    Répondre aux besoins spécifiques de l’entreprise tout en respectant ses contraintes opérationnelles et budgétaires.

 
2. Étapes clés du projet
- Gestion de projet et évaluation des besoins

    - Analyse initiale :

        Identification des risques potentiels pour l'entreprise.

        Évaluation des besoins en sécurité et des contraintes opérationnelles (budget, infrastructure).

        Définition des enjeux clés, comme la protection des données sensibles et la conformité réglementaire.

    - Planification :

        Élaboration d’un plan de projet détaillé incluant les délais, les étapes, et les livrables attendus.

- Recherche et choix des solutions techniques

    - Étude comparative des outils disponibles :

        Analyse des fonctionnalités, coûts, et performances des solutions sur le marché.

        - Choix des technologies adaptées en fonction des besoins identifiés :

            SIEM : Splunk pour la collecte et la corrélation des logs.

            SOAR : Splunk SOAR pour l’automatisation des réponses aux incidents.

            EDR : Elastic Stack pour la surveillance et la détection des endpoints.

            IPS/IDS : Snort, déployé dans un firewall pfSense, pour la prévention et la détection des intrusions réseau.

- Implémentation des solutions

    - Installation et configuration :

        Déploiement du SIEM (Splunk) en mode distribué, avec séparation des rôles entre Search Head et Indexer, pour la collecte et l'analyse des logs en temps réel

        Intégration du SOAR (Splunk SOAR) pour automatiser les flux de travail et les réponses aux incidents.

        Mise en place de l’EDR (Elastic Stack) pour surveiller les endpoints et identifier les comportements suspects.

        Snort a été déployé dans un firewall pfSense, permettant une détection et une prévention des intrusions réseau en analysant le trafic entrant et sortant.

        Configuration du Snort dans pfSense pour fournir des alertes en temps réel en cas d’intrusion ou de comportement suspect sur le réseau.

    - Tests et validation :

        Réalisation de scénarios de test pour valider l’efficacité des outils et des processus.

        Ajustement des configurations pour garantir une détection et une réponse optimales.

 
3. Résultats et Impact

    SOC opérationnel : Un environnement sécurisé capable de détecter et de répondre aux incidents en temps réel.

    Réduction des risques : Amélioration significative de la sécurité grâce à une détection proactive des menaces.

    Automatisation des processus : Réduction du temps de réponse aux incidents grâce au SOAR.

    Optimisation des ressources : Surveillance centralisée et intégration des outils pour un suivi efficace des endpoints et du réseau.

 
4. Outils et technologies utilisés

    Splunk (SIEM) : Collecte et corrélation des logs pour une surveillance en temps réel.

    Splunk SOAR : Automatisation des flux de réponse aux incidents.

    Elastic Stack (EDR) : Détection des menaces sur les endpoints.

    Snort (IPS/IDS) : Prévention et détection des intrusions réseau, déployé dans un firewall pfSense pour analyser le trafic réseau et détecter les anomalies.

​
5. Apprentissage et défis relevés

    Défi : Assurer une intégration fluide entre les différentes technologies tout en respectant les contraintes budgétaires.

    Solution : Une approche méthodique avec des tests réguliers pour garantir la compatibilité et l’efficacité des outils.

    Apprentissage : Développement des compétences en gestion de projet de sécurité, en configuration d’outils SIEM/EDR/IDS, et en automatisation des processus avec SOAR.

6. Rôle personnel

    Gestion de projet : Coordination des équipes et suivi des étapes clés.

    Analyse des besoins : Identification des risques et des contraintes spécifiques à l’entreprise.

    Recherche et choix des solutions techniques adaptées.

    Implémentation et configuration des outils SIEM, SOAR, EDR, et IPS/IDS, y compris le déploiement de Snort dans pfSense.

    Tests, validation, et documentation des processus.
