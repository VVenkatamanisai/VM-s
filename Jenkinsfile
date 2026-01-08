pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning GitHub repository'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage executed'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage executed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage executed'
            }
        }
    }
}
