pipeline {  
    
    environment { registry = "http://localhost:5000"}  
    agent any  
    
    stages {
    
        stage('Building image') {
      
            steps{
        
                script {
          
                    docker.build registry + ":$BUILD_NUMBER"
        
                }
      
            }
    
        }
  
    }

}
