Learn how to deploy your React app with minimal configuration, using Now.

Steps:
1. Install now dependency
    
    `npm install -g now`
2. Create file now.json
3. Add now-build into package.json

    `"now-build": "react-scripts build && mv build dist"`
4. Deploy the application
    
    `now`