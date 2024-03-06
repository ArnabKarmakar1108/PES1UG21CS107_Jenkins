pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                ech 'Building...'
                // Your build commands here
                // For example:
                // sh 'make'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing...'
                // Your test commands here
                // For example:
                // sh 'make test'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Your deployment commands here
                // For example:
                // sh 'make deploy'
            }
        }
    }
    
    post {
        failure {
            echo 'Pipeline failed!'
        }
    }
}
