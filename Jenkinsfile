pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'docker build -t tomcat:ans .'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
