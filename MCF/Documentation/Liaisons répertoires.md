# Les liaisons répertoires 

Les liaisons répertoires sont des scripts qui permettent de récupérer dans IsaGED des documents à partir de sources externes via des répertoires Windows. Ils peuvent être configurés pour cibler précisément les fichiers à intégrer en utilisant une nomenclature spécifique.

Voici un exemple de fonctionnement de la liaison répertoire dans le cadre d'une GED pour experts-comptables :

- Un expert-comptable enregistre un bulletin de salaire dans un répertoire Windows localisé sur son ordinateur.
- Le script de liaison répertoire surveille régulièrement ce répertoire et détecte le nouveau document.
- Le script copie le document dans la GED, dans la section du dossier client correspondant (déterminée à partir de la nomenclature du répertoire ou du nom du fichier).
- Le document est maintenant disponible dans la GED et peut être consulté ou partagé par tous les utilisateurs autorisés.

On aurait par exemple paramétré cette liaison répertoire avec /[Numéro de client]/[Année]/[Type de document]/[Nom du document] et ainsi si le document /12345/2020/Factures/Facture du mois de janvier.pdf est déposé, il sera intégré à l'emplacement voulu dans la GED.

L'intérêt des liaisons répertoires est de permettre de centraliser tous les documents de l'entreprise dans une seule GED, ce qui facilite leur gestion et leur consultation. Dans le cas du Publisher, ça permet de faciliter la remontée des documents sur MyCompanyFiles avec une source unique de données.

Vous pouvez mettre en place ces liaisons répertoires pour intégrer les documents provenant de SILAE via les liaisons répertoires : 