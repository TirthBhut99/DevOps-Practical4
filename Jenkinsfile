pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'HTML project - No build required'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests available'
            }
        }

        stage('Deploy') {
            steps {
                bat 'dir'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
