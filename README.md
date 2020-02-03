# EC2_RHEL_SETUP
Steps to be followed after creating new EC2 RHEL instance

To setup root user password(not recommended) refer AWS EC2 documentation 

Install Java : 
    sudo yum install java-11-openjdk-devel  
    (or)  
    sudo yum install java-1.8.0-openjdk-devel  
    
INSTALL VIM :  
  sudo yum install vim  
  
Set JAVA_HOME and OTHER REQUIRED ENV VARIABLES:  
    RHEL installs java in /usr/lib/jvm/java-11-openjdk-11.0.6.10-0.el8_1.x86_64/bin/java  
    vim ~/.bashrc  
    
    alias rm='rm -i'  
    alias cp='cp -i'  
    alias mv='mv -i'  
    export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-11.0.6.10-0.el8_1.x86_64/bin/java  


sudo yum install zip  
sudo yum install unzip  


