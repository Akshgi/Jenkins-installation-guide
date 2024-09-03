# Jenkins-installation-guide
How to install the Jenkins:
Installation of Java:
sudo apt update
sudo apt install fontconfig openjdk-17-jre

Install Key for jenkins :
sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key

echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null

installation of jenkins pn Linux Ubuntu:
sudo apt-get update
sudo apt-get install jenkins
