pipeline {
    agent { 
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
    post {
        always {
            echo 'This always runs'
        }
    }
}
