pipeline {
     
     agent {
              stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
         docker { image 'node:7-alpine' }
     }

}
