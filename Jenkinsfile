pipeline {
    agent {
        docker {
            image 'docker:compose'
            args '-v /var/run/docker.sock:/var/run/docker.sock'
        }
    }
    stages {
        stage('Deploy') {
            steps {
                sh 'docker-compose up -d'
            }
        }
    }
}
