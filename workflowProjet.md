
WORKFLOW PROJET SQUAD STANFORD

1. GITHUB

Fork du repo Stanford

Nouveau projet dans PyCharm
Create from Version control
coller URL du projet forké sur mon github
choisir nom de dossier local (soit même nom que repo Stanford soit autre)

On aurait pu juste cloner Stanford en local mais on crée un repo projet sur Github pour simu collab projet.

Maintenir mon clone uptodate avec modifs faites par Stanford:
https://docs.github.com/en/get-started/quickstart/fork-a-repo

cd robustqa
git remote -v #voir les 2 origins fetch/push
git remote add upstream https://github.com/michiyasunaga/robustqa.git
Le remote du projet PyCharm est sur mon github, où le .git s'appelle "origin"


2. CONDA ENV
Créa env spécial projet
->conda env create -f environment.yml
Activation
->source activate robustqa
Note: Remember to do this each time you work on your code.







