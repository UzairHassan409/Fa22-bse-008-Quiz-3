pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Compiling Java code...'
                bat 'javac main.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running Java program...'
                bat 'java main'
            }
        }
    }
}
