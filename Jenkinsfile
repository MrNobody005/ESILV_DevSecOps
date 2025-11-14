/* Requires the Docker Pipeline plugin */
pipeline {
    agent { any { image 'node:24.11.0-alpine3.22' } }
    stages {
        stage('build') {
            steps {
                bat 'node --version'
            }
        }
    }
}
