Description
Repository for the front-end developed with Nest.js (Backend).

Important: The Apache Kafka and Golang applications must be running first.

Configure /etc/hosts
Communication between applications is done directly through the machine's network. For this, it's necessary to configure an address that all Docker containers can access.

Add to your /etc/hosts (for Windows the path is C:\Windows\system32\drivers\etc\hosts):
127.0.0.1 host.docker.internal

On all operating systems, it's necessary to open the program to edit the hosts as the machine's Administrator or root.

Run the application

Execute the command:
docker-compose up
Access http://localhost:3000/routes.

