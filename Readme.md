## This is a simple implementation of a CI and CD workflow

1. User edit and works on node.js server
2. User git commits 
3. User push to this github 
4. The directory gets build into a docker container
5. Digitalocean droplet pulls the docker container
6. Digitalocean droplet runs the docker container on port 8081
7. After about a min or so the website can be run on http://139.59.125.14:8081/
The user can then see the nodejs app on port 8081 from web preview

This project is using buddy.works, it uses GUI to setup CI/CD pipeline.


