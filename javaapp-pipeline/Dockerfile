FROM ubuntu                                                                                                             
RUN apt update -y                                                                
RUN apt install git maven -y                                                     
RUN git clone https://github.com/pranay-meka/jenkins_docker.git                          
RUN cd jenkins_docker/javaapp-pipeline/ && mvn clean package
CMD ["java", "-jar", "jenkins_docker/javaapp-pipeline/target/java-sample-21-1.0.0.jar"]
