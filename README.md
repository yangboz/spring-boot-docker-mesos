# spring-boot-docker-mesos
Walk through the process of building a Docker image for running a Spring Boot application on Mesos framework.

## Mesos 

http://mesos.apache.org/gettingstarted/

####Start Mesos server: 

```./bin/mesos-master.sh --ip=127.0.0.1 --work_dir=/var/tmp```

###Start Mesos slave: 
```
./bin/mesos-slave.sh --master=127.0.0.1:5050 --work_dir=/var/tmp
```

###Open the Mesos web page: http://127.0.0.1:5050

## Reference

Spring-boot-docker:https://spring.io/guides/gs/spring-boot-docker/

Mesos on Macosx:https://kolovos.wordpress.com/2014/05/30/building-apache-mesos-on-mac-os-x-mavericks/

Minimesos:https://minimesos.org/

Spring-boot-mesos:http://container-solutions.com/mesos-starter/

Jenkins+Mesos:https://wiki.jenkins-ci.org/display/JENKINS/Mesos+Plugin
