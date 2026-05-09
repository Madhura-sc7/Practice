pipeline {
    agent any

    stages {

        stage('Git Checkout') {
            steps {
                git 'https://github.com/Madhura-sc7/Practice.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }
    }
}
