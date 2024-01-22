# Description
It's just a simple *hello-world* app. You could use it as a *boilerplate* for your NodeJS app.

# Run
I've created a Dockerfile so there's no need to install node. This means you need to have docker installed on your machine.
 ```
 docker build -t nodejs-helloworld .
 docker run nodejs-helloworld
 ```

 In case you want to run it directly with node:
 ```
node index.js
 ```
