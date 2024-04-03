pipeline {
    agent any

    stages {
        stage('npm install') {
            steps {
                bat 'npm install'
            }
        }
        stage('npm audit') {
            steps {
                bat 'npm audit'
            }
        }
        stage('npm tests') {
            steps {
                bat 'npm run test'
            }
        }
        
    }
}