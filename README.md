
Git global setup
```
git config --global user.name "LAWRENCE, PATRICK"
git config --global user.email "patrickclawrence@gmail.com"
```

Create a new repository
```
git clone git@REPO_LOCATION
cd FOLDER
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```

Existing folder or Git repository
```
cd existing_folder
git init
git remote add origin git@origin-p4gs.rws.ad.ea.com:hub3/hub3_analytics.git
git add .
git commit
git push -u origin master
```

Setting up a Node Project
```
node -v (Should be v8.9.1)
npm -v (Should be 5.5.1)
npm init
echo node_modules >> .gitignore
vim package.json (Add `"start": "node index.js"` under scripts and `"lint": "eslint index.js"`)
npm i --save-dev eslint (lint rules added seperately)
```

Setting up Koa
```
npm i koa
```
