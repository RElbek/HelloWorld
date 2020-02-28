pipeline {
     
     agent {
              stages {
        stage('Test') {
            steps {
                sh 'echo $PATH'
                sh 'node --version'
            }
        }
    }
         docker { image 'node:7-alpine' }
     }

}
