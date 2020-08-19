# sujets-AMC
Sujets lycée de questionnaire AMC

Des ressources AMC pour le lycée, il faut compiler certains projets avec pythontex. Pour cela, mettre le fichier prePythonTex4AMC dans le dossier du  projet.
Il faut que pythontex soit installé (https://www.ctan.org/pkg/pythontex) et que la ligne "python3 /usr/share/texmf-dist/scripts/pythontex/pythontex3.py $AMC_JOBNAME.pytxcode" pointe correctement sur pythontex.py (ou pythontex3.py dans l'exemple car j'utilise python 3)

Un fichier csv (référencé sur cette ligne "\csvreader[head to column names]{../liste.csv}{}{\sujet}" contient la liste des noms des eleves afin de générer les sujets avec les noms pré-remplis.

Le format du fichier csv est: nom,prenom,id (à garder comme premiere ligne)

Un exemple du sujet devrait être présent dans chasque projet, fichier DOC-sujet.pdf afin de visualiser le rendu.
