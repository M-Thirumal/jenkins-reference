###Docker installation
* To install latest LTS
    
    `docker pull jenkins/jenkins:lts`
   
* To install latest weekly version

    `docker pull jenkins/jenkins`
    
* To Run the jenkins in docker

    `docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts`
    
    to run in background with bind volume
    
    `sudo docker run -d -v jenkins_home:/var/jenkins_home -p 8080:8080 -p 50000:50000 jenkins/jenkins`
   
* Copy the password from the terminal/`/var/lib/docker/volumes/jenkins_home/_data/secrets/initialAdminPassword` and paste it in browser and set the admin account
    
    [http://localhost:8080](http://localhost:8080)
    
  
