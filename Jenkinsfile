pipeline {
    agent { docker {image 'node:16.13.2'} }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
