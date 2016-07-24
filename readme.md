https://github.com/ufoscout/docker-oracle-11g

docker build -t jhouzard/oracle-11g-ee .
docker run --privileged -d jhouzard/oracle-11g-ee --name oracle-11g
docker exec -ti <name> sudo -u oracle -i bash -c "sqlplus / AS SYSDBA"
