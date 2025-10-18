pipeline {
    agent { label 'windows' }
    stages {
        stage('Install dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Test') { 
            steps {
                bat 'npm test' 
            }
        }
    }
}