pipeline {
    agent any

    tools {
        nodejs 'node-16.18.1'
    }

    stages {
        stage('Build Image') {
            steps {
                echo '==============build version============='
                sh 'sudo docker-compose up -d --build'
            }
        }
    }
}