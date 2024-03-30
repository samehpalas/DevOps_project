mkdir jenkins war
chmod 777 -R jenkins war
docker compose up -d

for jenkins to install plugins; start with apt update
after mvn install phase, cp target/*.war /mnt for tomcat deployment

