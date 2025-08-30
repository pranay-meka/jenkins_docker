FROM ubuntu:26.10                                                                                                             
RUN apt update -y                                                                
RUN apt install git maven -y                                                     
RUN git clone https://github.com/artisantek/jenkins.git                          
RUN cd jenkins/javaapp-pipeline/ && mvn clean package
//CMD ["java", "-jar", "jenkins/javaapp-standalone/target/java-sample-21-1.0.0.jar"]
