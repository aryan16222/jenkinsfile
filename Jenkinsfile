pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Building the application..."
                // Example build command
                sh 'echo Build Stage Completed'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                // Example test command
                sh 'echo Test Stage Completed'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application to server..."
                // Example deploy command
                sh 'echo Deployment Successful'
            }
        }

        stage('Monitor') {
            steps {
                echo "Monitoring application..."
                sh 'echo Monitoring Started'
            }
        }

    }
}
