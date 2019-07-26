pipeline {
    agent any
    stages {
       stage('Print mothods') {
            steps {
               git 'https://github.com/revitalb10/MySoftware.git'
            }
        }
       stage('Build') {
            steps {
               bat 'python MySoftware.py'
            }
        }      
    }
}
