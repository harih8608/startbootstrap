pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                script {
                    // Checkout code from GitHub repository
                    git 'https://github.com/harih8608/startbootstrap.git'
                }
            }
        }

        stage('Build') {
            steps {
                script {
                    // Your build commands here
                    sh 'echo "Build step"'
                }
            }
        }
    }
}
