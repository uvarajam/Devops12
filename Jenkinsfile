
pipeline {
    agent any
    stages {
          Stage ('checkout') {
              Steps {
              checkout scm 
           }
              
       }
    stage('pack the file') {
        Steps {
    sh "tar -cvf data.tar.gz file abc"
} 
    
  }
        
    }
}

         
