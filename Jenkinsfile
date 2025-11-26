pipeline {
    agent any

    stages {

        stage('Docker Login') {
            steps {
                withCredentials([usernamePassword(credentialsId: 'dockerhub',
                    usernameVariable: 'DOCKER_USERNAME',
                    passwordVariable: 'DOCKER_PASSWORD')]) {

                    sh 'docker login -u $DOCKER_USERNAME -p $DOCKER_PASSWORD'
                }
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t vijeesh13/react-app:latest .'
            }
        }

        stage('Push Docker Image') {
            steps {
                sh 'docker push vijeesh13/react-app:latest'
            }
        }
    }
}

