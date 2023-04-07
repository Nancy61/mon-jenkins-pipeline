pipeline {
    agent any 
    
    stages{
        stage('Build') {
            steps{
                sh 'echo "Building testing branch"'
            }
        }
        stage('Test') {
            steps{
                sh 'echo "Testing testing branch"'
            }
        }
        stage('Deploy') {
            steps{
                sh 'echo "Deploying on testing branch"'
            }
        }
    }
}
