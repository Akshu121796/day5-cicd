pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
                echo 'GitHub checkout completed.'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage completed.'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage completed.'
            }
        }
    }
}
