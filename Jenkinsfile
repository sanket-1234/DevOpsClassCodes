pipeline {
    agent any 
    stages {
        stage ('build') {
            steps {
                echo " Building"
                sh 'maven compile'
            }
        }
        stage ('test') {
            steps {
                echo "Test"
                sh 'test'
            }
        }
    }
}
