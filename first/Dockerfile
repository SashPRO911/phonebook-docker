FROM openjdk:8
RUN	apt-get install wget && \
	mkdir /myapp && \
	cd /myapp && \
	wget https://github.com/SashPRO911/phonebook/releases/download/V1.1/phonebook.jar 
CMD ["java", "-cp", "/myapp/phonebook.jar", "com.phonebook.PhonebookApplication"]
