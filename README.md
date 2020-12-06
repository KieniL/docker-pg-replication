# PostgresSql Replication for Docker

Read this [blog post](https://medium.com/@2hamed/replicating-postgres-inside-docker-the-how-to-3244dc2305be).


run docker-compose up -d

With this command a primary / replica architecture is deployed with the nubmer of replicas defined as services.

if you run the replica only for backend access and don't want to access from outside remove the port exposing
