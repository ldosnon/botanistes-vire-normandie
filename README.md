# botanistes-vire-normandie
Interactifs Botanistes sur Musée Vire Normandie

# Procédure d'installation Electron
1. Dans le terminal se rendre dans le répertoire 
2. Initier un projet Electron : 
    npm init -y
    npm i --save-dev electron
<<<<<<< HEAD
3. Ignorer le répertoire "node_modules" dans .gitignore

# modif dans la config

"scripts": {
        "start": "electron ."
    }

     "main": "main.js",

# install de electron forge pour généreer les apps

npx @electron-forge/cli import

# généraion de l'app
npm run make
=======
3. Ingnorer le répertoire "node_modules" dans .gitignore

# Paramétrage package .json
 "scripts": {
    "start": "electron ."
  },

"main": "main.js",
>>>>>>> main
