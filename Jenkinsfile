pipeline {
    agent any
    stages {
        stage('Stage 1 - Check Python version') {
            steps {
                sh 'python --version'
            }
        }
        stage('Stage 2 - Run Python File') {
            steps {
                sh 'python file.py'
            }
        }
    }
}
