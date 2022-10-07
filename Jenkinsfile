
pipeline {
    agent any
    stages {
          stage ('checkout') {
              steps {
              checkout scm 
           }
              
       }
    stage('pack the file') {
        steps {
    tar -cvf  file abc
} 
    
  }
        
    }
}

         
