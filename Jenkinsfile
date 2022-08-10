pipeline {
    agent any
    stages {
        stage('DOCKER CONTAINER STATUS') {
            steps {
                sh'/home/ubuntu/status.sh' ${STATUS}
            }
            stage('DOCKER CONTAINER START') {
            steps {
                sh'/home/ubuntu/start.sh' ${START}
            }
            stage('DOCKER CONTAINER STOP') {
            steps {
                sh'/home/ubuntu/stop.sh' ${STOP}
            }
            stage('DOCKER CONTAINER STATUS') {
            steps {
                sh'/home/ubuntu/abc.sh' ${STATUS}
            }
            stage('DOCKER CONTAINER RESTART') {
            steps {
                sh'/home/ubuntu/restart.sh' ${RESTART}
            }
        }
    }
}
