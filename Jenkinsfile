pipeline {
    agent { docker 'maven:3.3.9-jdk-8-alpine' }
    stages {
        stage('Build') {
            steps {
                echo 'Building test pull request3'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing test pull request3'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying test pull request3'
            }
        }
    }
}
