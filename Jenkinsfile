pipeline {
    agent any

    stages {
        stage('Build') {
            sh './gradlew clean build'
        }
        stage('Test') {
            echo 'test'
        }
    }
}