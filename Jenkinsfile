pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Building from Jenkinsfile..."
            }
        }

        stage('Test') {
            steps {
                echo "Testing from Jenkinsfile..."
            }
        }
    }
}
