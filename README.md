# heroku-deploy
deployer votre application sur heroku

 s'inscrire   signup.heroku.com

-  Create App (Créer l’application) dans heroku 

- assurer bien que votre projet contient deja un git init au moins 

- ligne de commande  : heroku login 

- heroku git:remote -a nom de votre app cree sur heroku 

- creer un fichier Procfile  qui contient web: node index.js  votre fichier de node 

- git add .  

- git -m "votre commit" 

- git push heroku master 

- aller sur le navigateur https:// (votre app cree).herokuapp.com/



- heroku logs   pour voir les logs

- heroku restart -a app_name      relancer l'application

- heroku maintenance    voir l'etat de l 'application 

- heroku maintenance:on  pour faire une maintenance 
