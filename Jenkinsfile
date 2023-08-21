pipeline {
    agent any

    stages {
        stage('Cleaning') {
            steps {
                mvn clean
            }
        }
        stage('Validating') {
            steps {
                mvn validate
            }
        }
        stage('Installing') {
            steps {
                mvn install
            }
        }
    }
}
