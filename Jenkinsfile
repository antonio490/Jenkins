/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.13.2-alpine3.21' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}


