pipeline {
    agent {
        docker {
            image 'node:lts-buster-slim' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh "npm run build"
            }
        }
        stage('Test') {
            steps {
                sh 'npm --version'
                sh "npm run build"
            }
        }
    }
}
