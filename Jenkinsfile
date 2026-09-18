 pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                sh 'echo "Build step placeholder — replace with your real build command"'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'echo "Test step placeholder — replace with your real test command"'
            }
        }
    }
}
