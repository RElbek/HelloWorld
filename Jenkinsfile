pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'echo $PATH'
                sh 'node --version'
            }
        }
    }
}
