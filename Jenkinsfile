pipeline {
    agent any
    stages {
        stage('Cleaning') {
            steps {
                bat "mvn clean"
            }
        }
        stage('Validating') {
            steps {
                bat "mvn validate"
            }
        }
        stage('Testing') {
            steps {
                bat "mvn test"
            }
        }
        stage('Installing') {
            steps {
                bat "mvn install"
            }
        }
    }
}
