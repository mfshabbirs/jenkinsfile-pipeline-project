pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'This is pipeline script triggered via GitHub webhook'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
