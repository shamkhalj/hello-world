pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'touch /tmp/createfromjen'
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
