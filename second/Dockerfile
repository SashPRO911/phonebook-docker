FROM maven:3-jdk-8
RUN mkdir /myapp && \
cd /myapp && \
git clone https://github.com/SashPRO911/phonebook && \
cd phonebook && \
mvn install 
CMD ["cp","/myapp/phonebook/target/phonebook.jar","/target/"]
