pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sudo apt-get update
                sudo apt-get install python3

                // Add your build steps here
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deployment steps here
            }
        }
    }
}
