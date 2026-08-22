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
                sh 'echo "Building Python Project..."'
            }
        }

        stage('Run') {
            steps {
                sh 'python3 app.py'
            }
        }

    }
}
