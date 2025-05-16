pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'echo Build stage running...'
            }
        }
        stage('Test') {
            steps {
                bat 'echo Running unit tests...'
            }
        }
        stage('Deploy') {
            steps {
                bat 'echo Deploying to staging environment...'
            }
        }
        stage('Success') {
            steps {
                bat 'echo Deployed!'
            }
        }
    }
}
// Developed By Janitha
