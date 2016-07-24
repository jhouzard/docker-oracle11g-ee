https://github.com/ufoscout/docker-oracle-11g

docker build -t jhouzard/oracle-11g-ee:v1 .
docker run -t -i jhouzard/oracle-11g-ee:v1 /bin/bash

docker exec -ti containerName sudo -u oracle -i bash -c "sqlplus / AS SYSDBA"
