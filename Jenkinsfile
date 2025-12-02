pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Compiling Java code...'
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running Java program...'
                sh 'java HelloWorld'
            }
        }
    }
}
