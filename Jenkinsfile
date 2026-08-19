pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                sh 'javac addition.java'
            }
        }

        stage('run') {
            steps {
                sh 'java addition'
            }
        }
    }
}
