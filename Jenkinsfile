pipeline {
    agent {
        docker { image 'ionic-builder:latest' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
