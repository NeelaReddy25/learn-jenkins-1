pipeline {
    agent {
        label 'AGENT-1'
    }
    stages {
        stage('Build'){
            steps {
                sh 'echo This is Build'
            }
        } 
        stage('Test') {
            steps {
                sh 'echo This is Test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo This is Deploy'
            }
        }
    }
}