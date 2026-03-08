pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/YOUR_USERNAME/cicd-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building application...'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                sh 'mkdir -p ~/deploy-demo'
                sh 'cp index.html ~/deploy-demo/'
            }
        }
    }
}