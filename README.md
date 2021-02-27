# botanistes-vire-normandie
Interactifs Botanistes sur Musée Vire Normandie

# Procédure d'installation Electron
1. Dans le terminal se rendre dans le répertoire 
2. Initier un projet Electron : 
    npm init -y
    npm i --save-dev electron
3. Ignorer le répertoire "node_modules" dans .gitignore

# modif dans la config

"scripts": {
        "start": "electron ."
    }

     "main": "main.js",