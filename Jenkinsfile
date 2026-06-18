pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/vikas-1421/MyGradleApp1.git'
            }
        }

        stage('Build') {
            steps {
                sh './gradlew clean build'
            }
        }

        stage('Run') {
            steps {
                sh './gradlew run'
            }
        }
    }
}
