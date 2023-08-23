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
        stage('Build') {
            steps {
                sh 'ionic build'
            }
        }
    }
}
