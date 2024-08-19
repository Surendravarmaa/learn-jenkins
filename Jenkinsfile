pipeline {
    agent {
        label 'AGENT-1'
    }
    options {
        // Timeout counter starts BEFORE agent is allocated
        timeout(time: 30, unit: 'MINUTES')
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo This is build stage'
            }
        }
        stage('Test') {
            steps {
                sh 'echo This is Test stage'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo This is Deploy Stage'
            }
        }
    }
}