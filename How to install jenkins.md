# JENKINS
1. Installing Jenkins on Ubuntu/Linux

Jenkins runs on Java, so we install Java first.

Steps:

Update system packages

sudo apt update
sudo apt upgrade -y


Install Java (JDK 11 or 17 is recommended)

sudo apt install fontconfig openjdk-17-jre -y


✅ Verify:

java -version


Add Jenkins repository key

curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
/usr/share/keyrings/jenkins-keyring.asc > /dev/null


Add Jenkins repository

echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
/etc/apt/sources.list.d/jenkins.list > /dev/null


Install Jenkins

sudo apt update
sudo apt install jenkins -y


Start & enable Jenkins service

sudo systemctl start jenkins
sudo systemctl enable jenkins


Check status

sudo systemctl status jenkins


Open firewall (default port 8080)

sudo ufw allow 8080
sudo ufw status


Access Jenkins
Open browser → http://localhost:8080

Get admin password

sudo cat /var/lib/jenkins/secrets/initialAdminPassword


Use this password to unlock Jenkins in browser.

🔹 2. Installing Jenkins on Windows

Download Jenkins .msi installer from:
👉 https://www.jenkins.io/download/

Run the installer → follow setup wizard.

It will install Jenkins as a Windows Service.

During installation, it asks for a Java path (point to JDK/JRE if not detected).

After installation, Jenkins starts automatically.

Default port: http://localhost:8080

Find admin password in:

C:\Program Files\Jenkins\secrets\initialAdminPassword


Open browser → http://localhost:8080 → enter password → install suggested plugins.
