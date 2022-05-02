# dnf update
# dnf install java-1.8.0-openjdk-devel  	#install JDK 8
OR
# dnf install java-11-openjdk-devel		#install JDK 11
java -version
set java_home



# cd /usr/local
# wget http://www-us.apache.org/dist/tomcat/tomcat-9/v9.0.24/bin/apache-tomcat-9.0.24.tar.gz
# tar -xvf apache-tomcat-9.0.24.tar.gz
# mv apache-tomcat-9.0.24 tomcat9
# pwd tomcat9/
# ls -l tomcat9/

useradd -r tomcat
# chown -R tomcat:tomcat /usr/local/tomcat9
# ls -l /usr/local/tomcat9

tomcat.service unit file under /etc/systemd/system/ 


# systemctl start tomcat.service
# systemctl enable tomcat.service
# systemctl status tomcat.service