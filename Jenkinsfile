pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
        stage('test') {
            steps {
                echo 'Kaya'
            }
        }
        stage('cast') {
            steps {
                echo 'Maya'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}