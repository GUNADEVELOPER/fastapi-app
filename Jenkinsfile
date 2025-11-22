pipeline {
    agent any
    stages {
        stage('Build Docker') { steps { sh 'docker build -t fastapi-app .' } }
        stage('Push to ECR') { steps { sh 'echo Push to AWS ECR placeholder' } }
    }
}