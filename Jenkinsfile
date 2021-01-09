pipeline {
  agent any 
  stages {
      stage ('source') {
        steps {
          git branch: 'test', url: 'git@diyvb:repos/gradle-greetings'
          stash name: 'test-sources', includes: 'build.gradle,/src/test'
          }
      }
      stage('build') {
      }
   }
  }
