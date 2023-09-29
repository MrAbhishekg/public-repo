pipeline {
    agent any
    stages {
        stage('call this job') {
            steps {
              sh "echo this is first job"
              sh "echo this is second job"
            }
        }
        stage('Test') {
            steps {
                sh "echo this is second"
                sh "echo this is fourth"
            }
        }
        stage('Deploy') {
            steps {
                sh "echo this is third"
            }
        }
    }
}
