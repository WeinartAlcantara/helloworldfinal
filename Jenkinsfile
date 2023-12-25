pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'echo "Building Hello World!"'
                }
            }
        }
        
        stage('Test') {
            steps {
                script {
                    sh 'echo "Testing Hello World!"'
                }
            }
        }
        
        stage('Deploy') {
            steps {
                script {
                    sh 'echo "Deploying Hello World!"'
                }
            }
        }
    }
}
