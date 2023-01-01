# Démarrage d'un nouveau client Agent Serveur





[TOC]



## Pré-rendez vous

Le client a signé pour un module de l'agent serveur (Publisher / Downloader / Lien GI).
Le CSM va prendre rendez-vous avec Arthur et le client pour lancer le projet de déploiement.
Il n'existe aucune information sur le contexte du client, hors CRM ou message Skype/Mail où le CSM a prévenu Arthur du contexte.

## Premier RDV

Préambule : Récupérer les informations du clients sur le CRM ou demander au CSM, pour avoir un minimum de contexte : module souscrit + quelle GED + taille du cabinet

Rendez-vous avec le client, et optionnellement le CSM.

### Cadrage du contexte

Je commence par me présenter, et je demande confirmation au cabinet son contexte si j'ai eu des informations.
"Donc si mes informations sont bonnes, vous avez souscrit à un Publisher et avec comme GED XXXX"
Une fois tout bien validé, je leur demande, si pour eux la notion de Publisher avec XXXX leur semble claire, ou si j'ai besoin de leur refaire une explication rapide.
En général, je refais une explication. Je leur explique les bases, on peut reprendre cette vidéo et utiliser en présentation l'article du centre d'aide associé :

https://www.loom.com/share/9b10ee916ad6450aa2d8f8498c990c85

[Agent serveur : 1 - Présentation des modules (mycompanyfiles.fr)](https://support.mycompanyfiles.fr/portal/fr/kb/articles/comprendre-l-agent-serveur-et-ses-fonctionnalités#2_Publisher)

### Récupération des informations via formulaire

Ensuite, je préviens le client que j'ai besoin de récolter quelques informations pour pouvoir cadrer son contexte et aborder les différents sujets.
Les échanges peuvent être longs, ce n'est pas un problème, ce formulaire est l'occasion d'informer le client aussi.
Pour le moment, voici le formulaire utilisé : [Contexte client - Agent serveur (google.com)](https://docs.google.com/forms/d/e/1FAIpQLSdsnqKE4r5pmFcU7DruPpm-dbiXxA0doDJPoGfLlfMQgMpWLw/viewform)

Quelle GED : on est censé déjà le savoir
Quel OCR : Toujours intéressant à savoir, surtout si le client a un Downloader, si il en a pas la question peut être passée.
Quelle GI : Quel est son outil de gestion interne, pour gérer sa base de client ?
Social : Est-ce que le client est sur SILAE ? Où sont stockés les documents produits, dans sa GED ou autre part ? On peut les récupérer ?
Intéressant de savoir comment il fait actuellement pour envoyer les pièces aux clients (envoi par mail est censé être interdit)
Autre GED : Le cabinet stocke-t-il des documents à d'autres endroits que la GED mentionnée ?

Dans "Résultat", synthétiser tout ce qui a été appris avant : au final que doit-on installer ? Simple Publisher lié à la GED ? Ou d'autres demandes ont été remontés ?

### Explication du mapping 

Nous proposons alors au client de lui expliquer le fichier de mapping, c'est à dire le fichier définissant les liens entre leur GED et l'arborescence MyCompanyFiles des clients.

J'ouvre alors le fichier de mapping correspondant à sa GED : [MyCompanyFiles | Mapping Centre d'aide](https://support.mycompanyfiles.fr/portal/fr/kb/equipe-support/agent-serveur/mapping)

Je lui dis que ce serait bien qu'après il nous fasse un partage d'écran de sa GED pour que l'on remplisse ensemble une ou deux lignes en exemples.

Je présente mon écran avec le fiche Excel, et leur explique que la 1ère colonne correspond à leur arborescence MCF et que si ils l'ont ou vont la changer, alors ils devront mettre la leur.
Ensuite j'explique la significaiton de chaque colonne :

- Arbo MCF : Chemin de destination des fichiers publiés. La variable AAAA correspond au fait que l'on classera les documents automatiquement par année

- Emplacement de leur GED : Répertoire où se trouvent les documents à classer dans le chemin MCF de la colonne A
- Filtres : Ensuite, selon la GED il peut y avoir différents filtres. L'idée étant de leur dire qu'on peut faire tous les filtres qui veulent en général tant qu'ils sont capables de l'exprimer. Donner un exemple : "Vous souhaitez remonter que les fichiers dans ce répertoire avec le mot clé "plaquette" et étant un fichier pdf"

Il faut qu'il définisse ces règles pour chaque ligne.
Une fois que j'ai fini un exemple, je leur dis qu'il va falloir maintenant qu'ils s'occupent de voir en interne pour toutes leurs règles. Et qu'ils peuvent me contacter par mail si ils ont des questions

### Explication des prochaines étapes

Maintenant que tout est expliqué, je leur explique les prochaines étapes :

- Côté cabinet

  - il doit remplir et m'envoyer le fichier Excel. Il pourra me poser des questions via le mail que je lui enverra.
  - il doit prévenir l'informaticien/hébergeur que MCF va intervenir pour installer un service Windows (On peut imaginer qu'on envoie par mail au client la procédure d'installation comme maintenant on peut les rendre autonome)

- Côté MCF : 

  - Je vais lui envoyer le fichier Excel qu'on a commencé à remplir ensemble par mail après la réunion
  - On s'occupe de l'installation technique (on est censé avoir récupéré les informations sur l'information/hébergeur)

  => Compter 2 semaines pour que tout le monde termine ses tâches

- Quand tout ça est terminé :

  - On paramètre l'outil selon leur fichier Excel => Compter 1 semaine
  - On met en mode de test l'agent pour ne traiter que les documents pour quelques clients de test
  - On prévoir un point avec le client à ce moment là pour lancer les tests et expliquer le fonctionnement d'un point de vue concret.

  => La phase de test peut prendre plus ou moins de temps. Mais disons quelques semaines car les aller retours font perdre du temps. Des points en visio font accélérer le process

  - On sort de la phase de test et on déploie sur tous les clients
  - Déploiement terminé

  

  ### Après le RDV

  - Penser à envoyer le mail au client avec le fichier Excel
  - Intégrer le client dans le Asana de déploiement : https://app.asana.com/0/1199716340242129/list
  - Copier/coller toutes les informations récoltées dans le formulaire + autres infos utiles dans la description de la tâche
  - Planifier la date d'installation

## Installation technique

Voir documentation dédiée



## Paramétrage du mapping

Voir documentation dédiée

## Recettage

