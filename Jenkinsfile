pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Compiling Java code'
                bat 'javac Main.java'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }
        stage('Run Application') {
            steps {
                echo 'Running Java application'
                bat 'java Main'
            }
        }
    }
}
