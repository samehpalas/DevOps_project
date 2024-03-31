Ensure EC2 SG inboud are opened with the specific ports
install docker: https://docs.docker.com/engine/install/ubuntu/


mkdir jenkins war
chmod 777 -R jenkins war
vim docker-compose.yml
docker compose up -d

for jenkins to install plugins; start with apt update
after mvn install phase, cp target/*.war /mnt for tomcat deployment

