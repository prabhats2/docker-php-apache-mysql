pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage ('Run Docker Compose') {
      steps{
        sh '/usr/local/bin/docker-compose up -d'
      }
    }
  }
}
