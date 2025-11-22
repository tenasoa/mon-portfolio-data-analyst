## **1. Python & Jupyter (1h)**

```
Tenasoa@TENASOA MINGW64 ~
$ python --version
Python 3.13.5

Tenasoa@TENASOA MINGW64 ~
$ conda --version
conda 25.5.1
```

**Test de Jupyter** :![](C:\Users\Tenasoa\Pictures\Screenshots\Capture d'écran 2025-11-22 232746.png)

**☑️ Checklist Python** :

- [x]  Anaconda installé
- [x]  Python 3.8+ confirmé
- [x]  Jupyter démarre sans erreur
- [x]  Test "Hello World" réussi

## **2. Bibliothèques Python essentielles (1h)**

```
bash# Ouvrez Terminal/Cmd et exécutez :

pip install pandas numpy matplotlib seaborn scikit-learn openpyxl mysql-connector-python

# Vérification (lancez Python) :
python

# Puis dans l'interpréteur Python :
>>> import pandas as pd
... import numpy as np
... import matplotlib.pyplot as plt
... import seaborn as sns
... from sklearn.preprocessing import StandardScaler
...
... print("✓ Toutes les bibliothèques chargées !")
...
✓ Toutes les bibliothèques chargées !
```

**☑️ Checklist bibliothèques** :

- [x]  pandas installé
- [x]  numpy installé
- [x]  matplotlib installé
- [x]  seaborn installé
- [x]  scikit-learn installé

## **3. SQL (0.5h)**

**Option 1 : MySQL local**

```
bash# Téléchargez MySQL Community Server :
# https://dev.mysql.com/downloads/mysql/

# Installation (suivez l'assistant)
# Port : 3306 (par défaut)
# Root password : [fait]

# Vérification (Terminal/Cmd) :
Tenasoa@TENASOA MINGW64 ~
$ mysql --version
C:\Program Files\MySQL\MySQL Server 9.5\bin\mysql.exe  Ver 9.5.0 for Win64 on x86_64 (MySQL Community Server - GPL)
```

**Option 2 : PostgreSQL local**

```
bash# Téléchargez depuis :
# https://www.postgresql.org/download/

# Installation:
# Port : 5432 (par défaut)
```

**Option 3 : SQLite (plus simple, recommandé pour démarrer)**

```
bash# SQLite est inclus avec Python
python

import sqlite3
conn = sqlite3.connect(':memory:')
print("✓ SQLite fonctionne !")
```

**GUI pour SQL (optionnel mais utile)** :

- [x] DBeaver (gratuit) : https://dbeaver.io/download/
- [x] MySQL Workbench (gratuit) : https://www.mysql.com/products/workbench/

**☑️ Checklist SQL** :

- [x]  MySQL OU PostgreSQL OU SQLite installé
- [x]  Connexion de test réussie
- [x]  DBeaver (ou équivalent) installé

## **4. Git & GitHub (1h)**

```
bash# Téléchargez Git :
# https://git-scm.com/download

# Vérification :
Tenasoa@TENASOA MINGW64 ~
$ git --version
git version 2.52.0.windows.1
```

**Configuration Git** :

```
bash# Remplacez par vos infos
git config --global user.name "Tenasoa"
git config --global user.email "o.tenasoa@gmail.com"

# Vérification :
git config --global user.name
Tenasoa
git config --global user.email
o.tenasoa@gmail.com
```

**Créez votre compte GitHub** :

1. Allez sur https://github.com/signup
2. Créez un compte avec un pseudo professionnel (ex: `jean-dupont-data` pas `pizza_lover_2007`)
3. Vérifiez votre email

**Créez votre premier repository** :

```
bash# Sur votre ordinateur, créez un dossier
mkdir mon-portfolio-data-analyst
cd mon-portfolio-data-analyst

# Initialisez Git
git init

# Créez un README.md
echo "# Mon Portfolio Data Analyst" > README.md

# Commitez
git add README.md
git commit -m "Initial commit : création du portfolio"

# Sur GitHub, créez un nouveau repo avec le même nom
# Puis connectez votre local au remote :
git remote add origin https://github.com/VOTRE_USERNAME/mon-portfolio-data-analyst.git
git branch -M main
git push -u origin main
```

![image-20251122233756622](C:\Users\Tenasoa\AppData\Roaming\Typora\typora-user-images\image-20251122233756622.png)

**Vérification** : Allez sur votre page GitHub, vous devez voir votre repo avec le README.

**☑️ Checklist Git/GitHub** :

- [x]  Git installé localement
- [x]  Compte GitHub créé
- [x]  Premier repo créé et pushé
- [x]  README visible sur GitHub

## **5. Éditeur de code (0.5h)**

**Options** :

- [x] **VS Code** (gratuit, super populaire) : https://code.visualstudio.com/
- [x] **PyCharm Community** (gratuit) : https://www.jetbrains.com/pycharm/

**Recommandation** : VS Code + extensions

**Extensions essentielles VS Code** :

- [x] Python
- [x] Jupyter
- [x] MySQL
- [x] Git Graph
- [x] Code Runner
- [x] Markdown Preview

**☑️ Checklist éditeur** :

- [x] VS Code Éditeur installé
- [x]  Extensions pertinentes installées
- [x]  Test : créez un script Python et exécutez-le

## **6. Outils optionnels mais utiles (0.5h)**

| Outil            | Utilité                         | Gratuit ? | Lien                                                         |
| :--------------- | :------------------------------ | :-------- | :----------------------------------------------------------- |
| Power BI Desktop | Dashboards (limite 10 fichiers) | Oui       | https://www.microsoft.com/en-us/download/details.aspx?id=58494 |



- [x] ```
  text# ✅ Configuration technique - Projet 1
  
  ## Langages & Environnements
  - [x] Python 3.8+ installé
  - [x] Anaconda/Miniconda installé
  - [x] Jupyter Notebook fonctionne
  - [x] Version Python testée
  
  ## Bibliothèques Python
  - [x] pandas
  - [x] numpy
  - [x] matplotlib
  - [x] seaborn
  - [x] scikit-learn
  
  ## Bases de données
  - [x] SQLite OU MySQL OU PostgreSQL installé
  - [x] Connexion de test réussie
  - [x] GUI SQL (DBeaver et Workbench) installé
  
  ## Version Control
  - [x] Git installé
  - [x] Compte GitHub créé
  - [x] Premier repo créé
  - [x] Connexion SSH ou HTTPS testée
  
  ## Éditeur de code
  - [x] Éditeur installé (VS Code/PyCharm)
  - [x] Extensions/plugins pertinents installés
  
  ## Outils bonus
  - [x] Notion ou Obsidian pour les notes
  - [x] Power BI Desktop (optionnel pour maintenant)
  - [ ] Google Colab testé (optionnel)
  
  ## Date de vérification : 22 novembre 2025
  Tout est prêt pour démarrer ! 🚀
  ```