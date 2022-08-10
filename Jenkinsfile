pipeline {
    agent any 
    tools {
        maven 'mymaven'
        jdk 'myjava'
    }   
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
