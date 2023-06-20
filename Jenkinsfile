pipeline {
  agent none
  stages {
    
    stage('Build Trading Front End') {
       agent {
          node {
            label 'kaniko'
          }
        }
      steps {
        container(name: 'kaniko') {
          sh "echo 'Connected to Git.'"
        }
      }
    }
    
}
