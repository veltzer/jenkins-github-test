pipeline {
    agent {
        docker { image 'python:3-slim' }
    }
    // agent any
    stages {
        stage('test') {
            steps {
                //sh 'python -m pytest'
                //sh 'pytest'
                sh 'python --version'
            }
        }
    }
}
