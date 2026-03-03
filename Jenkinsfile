pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the Java source code 2'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled Java code.2'
                sh 'java Hello'
            }
        }
    }
}
