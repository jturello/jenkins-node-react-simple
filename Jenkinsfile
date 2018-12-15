pipeline {
    agent { docker { image 'node:10.14.2' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
