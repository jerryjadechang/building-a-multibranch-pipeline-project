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
            }
        }
        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}
