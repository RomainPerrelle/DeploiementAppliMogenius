# DeploiementAppliMogenius
Déployer une application simple sur la plateforme Mogenius

Commande pour créer l'image docker : 
  Build l'image:
    docker build -t image5 . 
  Voir la liste des images
    docker image
  run l'image (80 port local)
    docker run -p 8080:80 image5

Sur Mogenius : 
  - Commencer par lier GitHub du projet au compte Mogenius
  - Dans le dashboard ajouter une nouvelle production, choisir "Bring your own code" et ajouter le lien du gitHub
  - Dans Ports & Domain, bien préciser le port local, dans notre cas 80
  - Cliquer sur start pour lancer le projet
  - Pour accéder au projet, cliquer sur hostname puis external hostname
