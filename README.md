# mongo-db-rancher
Mongodb using the /data/db directory on the host for persistent storage. Replication with the help of Ranchers mongodb conf.


Using for example 3 hosts it will put one container on each host running a mongodb instance, replication between them and a /data/db directory on the host.
