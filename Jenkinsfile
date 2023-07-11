pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                touch /tmp/createfromjen
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
