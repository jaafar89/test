pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'jar cf test.war' 
            }
        }
    }
}