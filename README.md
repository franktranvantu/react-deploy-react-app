Learn how to deploy and host a React app on GitHub Pages, a free hosting solution provided by GitHub that lets others view your repository as a static website.

Steps:
1. Add homepage to package.json
    
    `"homepage": "http://myname.github.io/myapp"`
2. Install gh-pages dependency

    `npm install --save gh-pages`
3. Add predeploy and deploy to package.json
    
    `"predeploy": "npm run build"`
    
     `"deploy": "gh-pages -d build"`