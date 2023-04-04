# Step 1

Initialisation du projet :
- Création d'une branche develop
- Création d'une branche master (pas protégée, par souci de praticité, la protection sera ajoutée à la fin)
- Création d'une branche pour l'ajout d'une landing page, merge sur develop

# Step 2

- Création d'une branche pour l'ajout de la page en français à partir de develop
- Merge de la branche sur develop
- Pas de merge sur master car pas de release

# Step 3

- Création d'une branche, 1 commit par page, merge sur develop
- Création d'une branche pour la version 1.0, merge de cette branche sur master, création d'un tag v1.0 sur master pour la release
- Rebase de develop sur master

# Step 4

- Création d'une branche, 1 commit par page, merge sur develop

# Step 5

- Création d'une branche hotfix depuis master
- Merge de cette branche dans master puis merge dans develop
- Création d'un nouveau tag v1.1

# Step 6

- Pour mettre en stand-by la release du step 4, on crée une branche v2.0 depuis develop
- On crée également une branche pour l'étape 6 et la création d'une page en néerlandais

# Step 7

- On checkout sur la branche v2.0, on crée une branche step7
- On effectue la modification, puis on merge step7 dans v2.0
- On merge v2.0 dans master et dans develop
- On crée un tag v2.0 sur master

# Step 8

- On crée une branche v3.0 à partir de develop
- On merge v3.0 dans master
- On crée un tag v3.0 sur master
- On rebase develop sur master (pas de commit d'avance entre v3.0 et develop)