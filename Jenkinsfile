pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'ls -lart'
                // sh 'mkdir test'
                
                sh 'mkdir test1 test2'
                sh 'ls -lart'
                // mkdir 
            }
        }
        stage('test'){
            steps{
                echo 'test'
                sh 'pwd'
            }
        }
    }
}
