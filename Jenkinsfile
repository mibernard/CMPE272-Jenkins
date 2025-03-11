pipeline {
    agent any

    environment {
        PATH = "/usr/local/bin:$PATH"
    }

    stages {
        stage('Test Docker') {
            steps {
                sh 'docker --version'
                sh 'docker run hello-world'
            }
        }
    }
}