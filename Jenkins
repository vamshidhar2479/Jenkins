pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // This stage checks out the code from your version control system
                
            }
        }
        
        stage('Build') {
            steps {
                // This stage builds your project
               
            }
        }
        
        stage('Test') {
            steps {
                // This stage runs tests for your project
                
            }
        }
        
        stage('Deploy') {
            steps {
                // This stage deploys your application (example: to a staging environment)
               echo 'success'
            }
        }
    }
    
    post {
        success {
            // This block runs when the pipeline is successful
            echo 'Pipeline successful! Deploy to production if needed.'
        }
        
        failure {
            // This block runs when the pipeline fails
            echo 'Pipeline failed! Investigate and fix the issues.'
        }
    }
}
