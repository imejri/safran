pipeline {
  agent any 
  stages {
      stage ('source') {
        steps {
          git branch: 'test', url: 'https://github.com/imejri/maven-project.git'
     
          }
      }
     
   }
  post {
    failure
     {
    sh 'echo "fin du pipeline en erreur"'
    }
  }
  }
