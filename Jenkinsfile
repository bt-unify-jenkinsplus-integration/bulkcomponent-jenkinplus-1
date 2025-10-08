pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sleep 2
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sleep 5
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sleep 2
                 // Fail the build
                error('Tests failed!')
            }
        }
    }
}
