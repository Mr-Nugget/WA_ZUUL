# API Gateway - ZUUL

## Présentation

Voici le microservice API Gateway ZUUL server. C'est le point d'entrée unique d'accès aux microservices de l'application Wild Adventure.

L'accès au microservice est sécurisé via un login et un mot de passe, configuré avec Spring Security.
On y trouve également la configuration des CORS Policy.

## Déploiement

Lancer le main de l'application via votre éditeur java (eclipse ou IntelliJ) ou en faisant un build du projet maven `mvn clean install` puis éxécutez le jar généré dans le dossier target via `java -jar ******.jar`
