* Create react-apps folder
npm i create-react-app (geen -g, ntb of dat echt nodig is)
npx create-react-app my-app
cd my-app
npm start
> http://localhost:3000/ opent in chrome met werkende startpagina
npm i npm-windows-upgrade
npx npm-windows-upgrade (skipped, node en npm zijn OK)

npx create-react-app authorquiz
cd authorquiz
npm start
* goto https://getbootstrap.com, open href in css naar CDN om de css te kopieren en bewaar deze als D:\Data\react-apps\click-counter\src\bootstrap.min.css
Import deze in App.js
npm i underscore // voor array functionaliteiten in authorquiz
npm i enzyme enzyme-adapter-react-16 --save-dev // testing library (ivm dev dependencies in juiste folder ivm package.json)
npm --save install office-ui-fabric-react

==== GIT created new repo react-apps ==========
git init (in d:\data\react-apps)
git remote add origin https://github.com/MJBoes/react-apps.git
Added .gitignore (content: node_modules/**)
git add . (authorquiz vervolgens uit de cache gehaald met git rm --cached authorquiz -f omdat deze al een git repo bevat)
git push -u origin master
in autorquiz: git remote add origin https://github.com/MJBoes/react-apps-authorquiz.git
git push -u origin master
===============================================
Router
npm i react-router-dom --save
=== Add react tools to Chrome ===
Google react dev tools
=== SSL ===
In firstreactapp\node_modules\react-scripts\scripts\start.js, add process.env.HTTPS = 'true'; on line 14
