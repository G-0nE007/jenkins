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
                echo 'Build step - No build needed for HTML/CSS'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy step - Deploying static files'
                // Example: Copy files to a web server
                sh 'cp -r * /path/to/webserver'
            }
        }
    }
}
