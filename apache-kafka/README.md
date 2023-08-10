Description
Repository for Apache Kafka (Backend).

Configure /etc/hosts
Communication between applications is done directly through the machine's network. For this, it's necessary to configure an address that all Docker containers can access.

Add to your /etc/hosts (for Windows the path is C:\Windows\system32\drivers\etc\hosts):

127.0.0.1 host.docker.internal

On all operating systems, it's necessary to open the program to edit the hosts as the machine's Administrator or root.

Run the application
Execute the command:

docker-compose up


When stopping the Kafka containers, remember to run docker-compose down to clear storage before running docker-compose up again, otherwise, it will throw an error when starting up.