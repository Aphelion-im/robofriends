# Deploy React App to Github Pages
Updated: 19-4-2021

## Deploy React App to Github Pages
* [Deploy to Github pages](https://create-react-app.dev/docs/deployment/#github-pages)

1. $ npm run build 
1. Create a new repository on Github
1. Push local React app to Github main branch
1. Add homepage to package.json: "homepage": "https://myusername.github.io/my-app",
1. $ npm install --save gh-pages
1. Add the following scripts in your package.json: "predeploy": "npm run build", "deploy": "gh-pages -d build",
1. $ npm run deploy
1. Github repo Settings > Pages > Source > Put on branch: gh-pages.
1. Enforce HTTPS.