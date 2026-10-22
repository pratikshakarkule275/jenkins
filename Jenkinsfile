pipeline {
    agent any

    stages {
        stage('Pull') {
            steps {
                git branch: 'main', url: 'https://github.com/pratikshakarkule275/batch25.git'
                echo "Git Pull Successful"
            }
        }

        stage('Build') {
            steps {
                echo "Build Successful"
            }
        }

        stage('Test') {
            steps {
                echo "Test Successful"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy Successful"
            }
        }
    }
}