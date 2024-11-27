pipeline {
    agent {
        docker { image 'node:22.11.0-alpine3.20' }
    }
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
        stage('Deploy') {
            steps {
                sh 'uname'
                sh 'cat /etc/*release*'
            }
        }
    }
}
