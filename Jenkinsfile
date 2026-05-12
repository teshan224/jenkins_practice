pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                echo 'Cloning Repository...'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Application...'
            }
        }

        stage('Test') {
            steps {
                sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Application...'
            }
        }
    }
}
