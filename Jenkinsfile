pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Build steps
            }
        }

        stage('Test') {
            steps {
                // Test steps
            }
        }

        stage('Deploy') {
            when {
                expression { branch == 'master' }
            }
            steps {
                // Deployment steps
            }
        }
    }

    post {
        success {
            // Actions to perform if the pipeline is successful
        }
    }
}
