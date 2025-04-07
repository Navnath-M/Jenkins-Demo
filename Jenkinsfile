pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                
            }
        }
        stage('Deploy Python') {
            steps {
                bat 'python hello.py'
                
            }
        }
    }
}
