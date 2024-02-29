pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'checkout...................................'
                git 'https://github.com/shyamsundarvarma/ant.git'
                
            }
        }
        stage('compile') {
            steps {
                echo 'compile..............................'
                sh 'ant compile'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...................................'
            }
        }
    }
}
