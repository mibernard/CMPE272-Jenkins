pipeline {
    agent any

    environment {
        PATH = "/usr/local/bin:$PATH"
    }

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the application..."'
                // Add build commands here
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
                // Add test commands here
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying the application..."'
                // Add deployment commands here
            }
        }
    }
}