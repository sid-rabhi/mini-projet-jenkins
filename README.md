# Mini-projet Jenkins

![pipeline ci/cd](images/CICD.png "pipeline ci/cd")

Ce projet Jenkins a été conçu pour automatiser les processus de construction, de test et de déploiement d'un site web statique disponible sur GitHub via le lien https://github.com/sid-rabhi/static-website-example/ .
Pour permettre l'intégration continue malgré un serveur Jenkins local, j'ai utilisé **Ngrok** pour exposer mon serveur Jenkins localement et lui attribuer une adresse IP publique. Un **Webhook** a été configuré pour déclencher automatiquement les workflows à chaque modification du projet, nécessitant cette adresse IP publique pour son bon fonctionnement.
De plus, des notifications sur **Slack** ont été intégrées dans le pipeline pour informer en temps réel des résultats des différents processus automatisés https://github.com/sid-rabhi/sid-slack-shared-library/.
Le fichier `Jenkinsfile` contient les étapes détaillées du pipeline, intégrant des processus de construction, de tests automatisés et de déploiement. Ce rapport fournit un aperçu complet du fonctionnement de chaque étape du pipeline, en mettant en évidence les avantages et les possibilités offertes par cette approche automatisée.

---

Auteur : Sid Ahmed Rabhi

Contexte : formation Bootcamp DevOps promotion 16

Centre de formation : Eazytraining

Période : novembre-décembre-janvier

Date : 06 janvier 2024

LinkedIn : https://www.linkedin.com/in/sid-ahmed-rabhi/

## Aperçu du pipeline CI/CD

![pipeline ci/cd](images/pipeline-jenkins.png "pipeline ci/cd")
