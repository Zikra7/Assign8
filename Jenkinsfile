pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac Helloworld.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java Helloworld'
            }
        }
        
    }
}
