Vérifier Node.js

Dans PowerShell :

node -v
npm -v

Si ça affiche des versions → c’est bon.
Sinon installe Node.js depuis son site officiel.

Créer un projet Next.js

Commande recommandée :

npx create-next-app@latest mon-projet

Remplace mon-projet par le nom que tu veux.

Ensuite il va te demander :

TypeScript ? → Yes (souvent mieux)
ESLint ? → Yes
Tailwind CSS ? → Yes si tu veux styliser facilement
src/ directory ? → comme tu veux
App Router ? → Yes (nouvelle version)
Turbopack ? → Yes possible
Entrer dans le projet
cd mon-projet
Lancer le serveur
npm run dev

Puis ouvre :

http://localhost:3000