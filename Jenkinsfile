pipeline {
  agent any 
  stages {
      stage ('source') {
        steps {
          git branch: 'master', url: 'https://github.com/imejri/maven-project.git'
     
          }
      }
     
   }
  post {
    sh echo "fin du pipeline"
  }
  }
