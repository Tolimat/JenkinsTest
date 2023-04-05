pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Tolimat/JenkinsTest.git'
            }
        }
        stage('Test') {
            steps {
                sh 'python3 main.py'
            }
        }
    }
}