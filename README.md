#How to use docker-compose to set up a Flask web server and a Redis cache to count page hits

Compose is a tool for defining and running multi-container Docker applications. 
With Compose, you use a YAML file to configure your application’s services. 
Then, with a single command, you create and start all the services from your configuration. 
Compose works in all environments: production, staging, development, testing, as well as CI workflows. 
Using Compose is basically a three-step process:
+ Define your app’s environment with a Dockerfile so it can be reproduced anywhere.
+ Define the services that make up your app in docker-compose.yml so they can be run together in an isolated environment.
+ Run docker-compose up and Compose starts and runs your entire app.

https://docs.docker.com/compose/gettingstarted/
On this page you build a simple Python web application running on Docker Compose. 
The application uses the Flask framework and maintains a hit counter in Redis. 
While the sample uses Python, the concepts demonstrated here should be understandable 
even if you’re not familiar with it.

Check web site with http://localhost:5000/
Refresh the page and see how the hit counter increments.
