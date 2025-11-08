pipeline {
    agent any
    
    stages {
        stage('Compilation HelloWorld') {
            steps {
                echo 'Compilation HelloWorld'
                sh 'javac HelloWorld.java'
            }
        }
        
        stage('Execution HelloWorld') {
            steps {
                echo 'Execution HelloWorld'
                sh 'java HelloWorld'
            }
        }
        
        stage('Compilation Merci') {
            steps {
                echo 'Compilation Merci'
                sh 'javac Merci.java'
            }
        }
        
        stage('Execution Merci') {
            steps {
                echo 'Execution Merci'
                sh 'java Merci'
            }
        }
        
        stage('Compilation DeRien') {
            steps {
                echo 'Compilation DeRien'
                sh 'javac DeRien.java'
            }
        }
        
        stage('Execution DeRien') {
            steps {
                echo 'Execution DeRien'
                sh 'java DeRien'
            }
        }
    }
    
    post {
        always {
            echo 'Pipeline terminée !'
        }
    }
}
