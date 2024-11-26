pipeline {
    agent any
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                sh 'pwd'
                sh 'ls -l'
                sh 'env'
                echo "${CI}"
            }
        }
        stage('Test') {
            steps {
                echo "testing..."
            }
        }
    }
}
