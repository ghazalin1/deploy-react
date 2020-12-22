# deploy-react 

# How to Deploy-react app in Git Hub through Command prompt in 1 minute. Simple Steps

Steps.

1. Open code in Visual studio and open terminal
2. Run npm install gh-pages --save-dev
3. Run  git remote add origin https://github.com/ghazalin1/repository-name.git  (deploy-react in this case)
4. Add "homepage": "http://ghazalin1.github.io/deploy-react", in package.json file
5. Add"predeploy": "npm run build",
    "deploy" : "gh-pages -d build"
    in "scripts".
6. Run npm run deploy on Terminal


#Run homepage to check http://ghazalin1.github.io/deploy-react/
    
