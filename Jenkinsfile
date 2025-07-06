pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat './gradlew clean build'
            }
        }
        stage('Run') {
            steps {
                echo 'Building..'
                bat './gradlew run'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                bat './gradlew test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying '
                //bat './gradlew deploy'
            }
        }
    }
}