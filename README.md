Évaluation – Git, GitHub, CI
Alexis BERT , Yassin EL ALAOUI

Les différences : 
switch/checkout = La commande git checkout permet de changer de branche et de mettre à jour les fichiers du repertoire de travail.
                  La commande git switch permet de passer d'une branche à l'autre.

pull/fetch = git fetch permet de récupérer les modifications présentes sur un serveur distant qu'on à pas encore.
             git pull met à jour la branche actuelle en fusionnant les changements de sa version sur le serveur distant. Cela ne concerne que la branche sur laquelle on se trouve.

rebase/revert = git rebase permet de déplacer une branche pour qu’elle parte d’un autre commit, comme si on l’avez créée à partir de celui-ci.
                git revert permet d'annuler des changements de commit.


Description des commandes :
tag = C'est une étiquette fixe qui est attachée à un commit, elle va signaler des versions clés d’un projet.

stash = Cette commande va mettre de côté temporairement les modifications en cours dans un espace de travail afin de pouvoir travailler sur d'autres tâches puis de récupérer ces changements plus tard.

release = C'est la version stable d'un projet


url github : https://github.com/AlexisBERT-Work/EvaluationGit

url pull-requests(5):
            - https://github.com/AlexisBERT-Work/EvaluationGit/pull/5
            - https://github.com/AlexisBERT-Work/EvaluationGit/pull/4
            - https://github.com/AlexisBERT-Work/EvaluationGit/pull/3
            - https://github.com/AlexisBERT-Work/EvaluationGit/pull/2
            - https://github.com/AlexisBERT-Work/EvaluationGit/pull/1


url request avec soucis de merge : 
            - https://github.com/AlexisBERT-Work/EvaluationGit/pull/8


description courte :
    - petite application qui ajoute des taches, un compteur et s'occupe de leurs complétions.

commandes utilisées :
    - git init -y
    - npm install
    - npm run test