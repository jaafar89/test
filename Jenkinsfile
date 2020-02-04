pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'jar cvf test.war' 
            }
        }
    }
}