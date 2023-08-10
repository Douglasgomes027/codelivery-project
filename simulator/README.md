Description
Repository for the front-end made with Golang (Backend).

Important: The Apache Kafka application must be running first.

Configure /etc/hosts
Communication between applications is done directly through the machine's network. For this, it is necessary to configure an address that all Docker containers can access.

Add to your /etc/hosts (for Windows the path is C:\Windows\system32\drivers\etc\hosts):

127.0.0.1 host.docker.internal

On all operating systems, it is necessary to open the program to edit the hosts as the machine's Administrator or root.

Run the application
Execute the commands:

docker-compose up -d
# Enter the container
docker-compose exec app bash
# Run the Golang application
go run main.go
