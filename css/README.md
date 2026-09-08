Project Creator Commands
========================
Run only when creating the project for the first time.

1) npm init -y
   → Creates package.json

2) npm install --save-dev http-server
   → Installs http-server and adds it to package.json

3) Edit package.json
   Add:

   "scripts": {
       "dev": "http-server ."
   }

4) npm run dev
   → Starts the development server


Developer Setup
===============
Run after cloning the Git repository.

1) git clone <repo-url>
2) cd <project-directory>
3) npm install
   → Installs all dependencies from package.json

4) npm run dev
   → Starts the development server