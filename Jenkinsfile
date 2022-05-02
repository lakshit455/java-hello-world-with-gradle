pipeline {
     agent any
     stages {
         
         stage('Build') {
             steps {                  
                  sh 'gradle clean build'
                  archiveArtifacts artifacts: '**/*.jar', followSymlinks: false
             }              
           
         }
     }
 }
