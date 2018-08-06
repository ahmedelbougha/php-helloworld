pipeline {
    agent { docker { image 'php' } }
    stages {
        stage('Build') {
            steps {
                bat 'set'
                sh 'php --version'
            }
        }
    }
}
