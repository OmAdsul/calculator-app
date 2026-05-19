pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building calculator app...'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 -m pytest'
            }
        }

        stage('Lint') {
            steps {
                sh 'python3 -m py_compile calculator.py'
            }
        }
    }
}