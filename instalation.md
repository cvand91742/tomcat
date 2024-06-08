### creation of VM use GCP or AWSv ##
### creation of VM use GCP or AWSv ##

cd /opt 

wget https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.89/bin/apache-tomcat-9.0.89.zip


## install unzip if available no need 
unzip apache-tomcat-9.0.89.zip 
apt install unzip -y

  501  apt install unzip -y
  502  unzip apache-tomcat-9.0.89.zip 
  503  cd /opt/
  504  unzip apache-tomcat-9.0.89.zip 
  505  ll
  506  mv apache-tomcat-9.0.89 tom9
  507  ll
  508  mv apache-tomcat-9.0.89 tom9
  509  unzip apache-tomcat-9.0.89.zip

## start tomcat 

cd tomcat/bin 

### excuet the start-up file in same location cd tomcat/bin ##

sh startup.sh

# give the excute permistions for all files if need * means all file ##

chmod +x * 

## statrt comcat 
cd /opt/tomcat/bin 
sh startup.sh  
## this will not run the file in bin 

## verification 
ps -ef | grep -t java 

## run the tomcat, it will crealy show tomcat is running. 
sh startup.sh 

