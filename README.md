"# Angular_structure_project" 
###Bootstrap CDN
https://www.bootstrapcdn.com/

### TypeScript
npm install typescript
tsc -init

### Typings
npm install typings
typings init
typings install dt~jquery dt~core-js  dt~node --global --save
 
 ### Concurently 
 npm install concurrently --save-dev

 ### dependencies
 npm install core-js node.js reflect-metadata exjs systemjs --save

 ##Production mode
 ### Compliation AOT
 npm install @angular/compiler-cli @angular/platform-server --save


 "node_modules/.bin/ngc" -p tsconfig-aot.json

 https://angular.io/guide/aot-compiler