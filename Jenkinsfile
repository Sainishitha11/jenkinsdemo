pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git branch: "main", utl: 'https://github.com/Sainishitha11/jenkinsdemo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                echo "Checking if HTML file exists"
                sh 'test -f index.html'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deployment successful"
            }
        }
    }
}
