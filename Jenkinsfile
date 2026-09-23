pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/ganeshkumars2024-ai/pip1.git'
            }
        }

        stage('Show Files') {
            steps {
                bat 'dir'
            }
        }
    }
}
