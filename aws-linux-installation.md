sudo yum install epel-release
sudo yum install docker
sudo yum-config-manager --enable epel
sudo yum install ansible
sudo yum install java-1.8.0-openjdk-devel
sudo wget http://repos.fedorapeople.org/repos/dchen/apache-maven/epel-apache-maven.repo -O /etc/yum.repos.d/epel-apache-maven.repo
sudo sed -i s/\$releasever/6/g /etc/yum.repos.d/epel-apache-maven.repo
sudo yum install -y apache-maven
mvn --version
sudo update-alternatives --config java
sudo update-alternatives --config javac
