###Docker installation
* To install latest LTS
    
    `docker pull jenkins/jenkins:lts`
   
* To install latest weekly version

    `docker pull jenkins/jenkins`
    
* To Run the jenkins in docker

    `docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts`
   
* Copy the password from the terminal and paste it in browser and set the admin account
    
    [http://localhost:8080](http://localhost:8080)
  