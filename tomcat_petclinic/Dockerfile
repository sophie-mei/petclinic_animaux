FROM tomcat:8.5.53-jdk8-openjdk

#WORKDIR /home/ivan/devops/projet/spring-framework-petclinic/target/
#WORKDIR /home/ivan/devops/projet/spring-petclinic-fitec2020/target/

COPY wait-for-it.sh /usr/local/tomcat/wait-for-it.sh

COPY petclinic.war /usr/local/tomcat/webapps/petclinic.war
