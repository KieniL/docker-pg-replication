# PostgresSql Replication for Docker

Read this [blog post](https://medium.com/@2hamed/replicating-postgres-inside-docker-the-how-to-3244dc2305be).


run docker-compose up -d --scale pg_replica=SCALE_NUMBER

With this command a primary / replica architecture is deployed with the replica defined as read replica based on the number specified.

if you run the replica only for backend access and don't want to access from outside remove the port exposing