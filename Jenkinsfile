// this is pipeline script
pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
