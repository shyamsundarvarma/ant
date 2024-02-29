pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                echo 'Deploying...................................'
                git 'https://github.com/shyamsundarvarma/ant.git'
                sh 'ant compile'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..............................'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...................................'
            }
        }
    }
}
