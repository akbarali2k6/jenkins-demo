pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello from Jenkins + GitHub!'
                sh 'python3 --version'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
                sh 'date'
            }
        }
    }
}
