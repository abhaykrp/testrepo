pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'ls' 
            }
        }
        stage('Test'){
            steps {
                sh 'touch a'
            }
        }
        stage('Deploy') {
            steps {
                sh 'env'
            }
        }
    }
}
