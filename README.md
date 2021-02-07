Before deploying a React application, you will need a production-ready build of the app. 

In this section, we'll create a static build that will optimize React code to run in browsers and download as fast as possible.

Steps:
1. Build the production application 
    
    `npm run build`
2. Install serve dependency

    `npm install -g serve`
3. Deploy application to the server
    
    `serve -s build`