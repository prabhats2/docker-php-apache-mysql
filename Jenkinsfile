pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage ('Run Docker Compose') {
      steps{
        sh 'docker-compose up -d'
      }
    }
  }
}
