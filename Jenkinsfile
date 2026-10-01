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
                bat 'javac adds.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Addition'
            }
        }
    }
}
