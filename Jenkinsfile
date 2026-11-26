pipeline {
    agent any
    stages{
        stage('Checkout'){
            steps{
                git branch:'main',url:'https://github.com/rohanshinde2004/Docker-Zero-to-Hero.git'
            }
        }
        stage('Build'){
            steps{
                echo "Building an Django application"
            }
        }
        stage('Test'){
            steps{
                echo "Testing an application"
            }
        }
        stage('Deployment'){
            steps{
                echo "Deploying an application"
            }
        }
    }
    post {
        success { echo "Deployment successfull" }
        failure { echo "Deployment failed"}
    }
}
