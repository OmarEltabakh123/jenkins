pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/OmarEltabakh123/basic-flask-app.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the Flask app...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the app...'
            }
        }
    }
}

