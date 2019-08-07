pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 7000:7000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}