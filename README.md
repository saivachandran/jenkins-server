# pull image from docker hub


$ docker pull jenkins/jenkins


# validate docker-compose file

$ docker-compose -f docker-compose.yml

# run docker-compose.yml

$ docker-compose up -d


# Access url from browser

http://ipaddress:8080

# copy jenkins password from jenkins conatiner

$ docker exec -it 0eea5c523151 cat /var/jenkins_home/secrets/initialAdminPassword


# installed suggested plugins

# signup username and password







