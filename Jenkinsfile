pipeline {
    agent any 

    stages {
        stage('Etape 1: Hello') {
            steps {
                bat 'javac HelloWorld.java'
                bat 'java HelloWorld'
            }
        }
        stage('Etape 2: Merci') {
            steps {
                bat 'javac Merci.java'
                bat 'java Merci'
            }
        }
        stage('Etape 3: DeRien') {
            steps {
                bat 'javac DeRien.java'
                bat 'java DeRien'
            }
        }
    }
}
