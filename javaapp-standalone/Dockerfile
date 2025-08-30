  FROM ubuntu:26.10                                                                                                             
  RUN apt update -y                                                                
  RUN apt install git maven -y                                                     
  RUN git clone https://github.com/artisantek/jenkins.git                          
  RUN cd jenkins/javaapp-standalone/ && mvn clean package
