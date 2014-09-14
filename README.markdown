# Introduction
Dans le cadre du premier TP évalué, vous aurez à vous familiariser avec Python. 
Spécifiquement, vous devrez lire des fichiers et créer une base de donnée
conforme qui recueille l'information contenue dans ces derniers. Pour ce faire,
vous devrez travailler en Python 3 et utiliser le module ``pymysql``.

J'ai préparé ici une liste de resources utiles pour apprendre le nécessaire
pour faire ce travail.

## Procédure pour utiliser Python3 sur Esilbac

```sh
ssh esilbac4a
module load python3
```

Puis, dans vos scripts Python, il sera important de se connecter à ``esilbac2``
comme nom d'hôte MySQL:

```python
import pymysql

con = pymysql.connect(
    host="esilbac2",
    user="p0123456",
    passwd="...",
    db="p0123456_bin3002",
)
```

## Ressources

*Important!* J'ai prepare un _notebook_ disponible dans ce repo. Vous pouvez aussi le 
visionner (sur nbviewer)[http://nbviewer.ipython.org/github/legaultmarc/demo_bin3002/blob/master/Tutorial.ipynb].

### Python

- (Le tutoriel officiel)[https://docs.python.org/3/tutorial/index.html]
- (Learn X in Y minutes)[http://learnxinyminutes.com/docs/python3/]

