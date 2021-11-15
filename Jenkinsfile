pipeline {
    agent none
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
