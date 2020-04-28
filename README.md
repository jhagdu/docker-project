# New Generation Voting

This is the infrastructure of docker on which e-voting site is running to provide the facilities of e-voting.

Clone or Download it then open terminal in base folder of it.  
Then to start the infrastructure, Run command

$ docker-compose up

If you don't want to see logs and want to run this in backgroung then use command

$ docker-compose up -d

On first start it will download the required container images, that are :-
1)	jhagdu/centos_httpd_php
2)	phpmyadmin/phpmyadmin
3)	mysql

Now after downloading these images the infrastructure is ready to use and now open localhost:8080 in base browser.
To manage database, open localhost:8081 and login their using Username: root and Password: toor
