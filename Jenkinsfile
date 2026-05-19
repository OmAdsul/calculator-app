pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 -m pytest'
            }
        }
    }
}