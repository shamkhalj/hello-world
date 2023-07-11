pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'docker build -t tomcat:jn .'
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
