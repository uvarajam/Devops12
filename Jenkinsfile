
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
    sh 'tar cvf file.tar file'
} 
    
  }
        
    }
}

         
