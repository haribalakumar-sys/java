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
                bat 'javac Addition.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Addition'
            }
        }
    }
}
