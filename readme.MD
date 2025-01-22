# CICD

manual steps to build the source code, run test cases, scan the code for static analystis using sonarqube, create artifact

and store the artifact into server like nexus

git clone
npm install
npm test
sonar scan
zip the application
push to nexus

we can automate these above steps using CICD

# jenkins installation

```
sudo curl -o /etc/yum.repos.d/jenkins.repo \
    https://pkg.jenkins.io/redhat/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat/jenkins.io-2023.key
sudo yum upgrade
# Add required dependencies for the jenkins package
sudo yum install fontconfig java-17-openjdk
sudo yum install jenkins
```

Ref: https://www.jenkins.io/doc/book/installing/linux/


