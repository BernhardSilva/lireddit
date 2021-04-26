//backend

npm init -y
npm i -D @types/node typescript
npm i -D ts-node
mkdir src
touch index.js
npx tsconfig.json
npm i -D nodemon

npm i @mikro-orm/cli @mikro-orm/core @mikro-orm/migrations @mikro-orm/postgresql pg

//postgres (obtain localhost and port)
ps -ef | grep postgres
netstat -noa | grep -i 5432
