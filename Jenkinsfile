pipeline {
    agent any

    stages {
        stage('DOCKER CONTAINER STOP') {
            steps {
                script {
                sh'/home/ubuntu/jenkins_docker/stop.sh'
                }
            }
        }
		stage('DOCKER CONTAINER START') {
            steps {
                script {
                sh'/home/ubuntu/jenkins_docker/start.sh'
                }
            }
        }
		stage('DOCKER CONTAINER RESTART') {
            steps {
                script {
                sh'/home/ubuntu/jenkins_docker/restart.sh'
                }
            }
        }
		
    }
}
