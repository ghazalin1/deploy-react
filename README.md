# deploy-react

# Deploy React App on GitHub in 1 minute. Simple steps

Run these commands on terminal

1. npm install gh-pages --save-dev
2. git remote add origin https://github.com/ghazalin1/deploy-react.git
3. Add this code on package.json file "homepage": "http://ghazalin1.github.io/repo-name",  (In this case deploy-react)
4. Add this code in "scripts" "predeploy": "npm run build",
    "deploy" : "gh-pages -d build"
5. npm run deploy

Run the homepage address https://ghazalin1.github.io/deploy-react/
