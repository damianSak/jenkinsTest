pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/damianSak/jenkinsTest.git'
                sh './mvnw clean compile'

            }
        }
    }
}