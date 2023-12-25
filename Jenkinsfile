pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                script {
                    sh 'chmod +x helloworld'
                }
            }
        }
        
        stage('Test') {
            steps {
                script {
                    sh './helloworld'
                }
            }
        }
        
        stage('Deploy') {
            steps {
                script {
                    echo 'Deployed)'
                }
            }
        }
    }
}
