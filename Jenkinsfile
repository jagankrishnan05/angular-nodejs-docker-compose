pipeline {
    agent any     
    stages {        
    // Running Docker container, make sure port 8082 is opened in 
    stage('Docker Run') {
     steps{
		 // sh "docker-compose down"
		 sh "sudo docker-compose up -d"
         }
      }
}
}
