pipeline {
    agent any // 1

    stages {
        stage('Build') { 
            steps {
                //#3
                echo ' building the application'
            }
        }
        stage('Test') { 
            steps {
                //#5
                echo ' testing the application'
            }
        }
        stage('Deploy') { 
            steps {
                //#7
                echo ' deploying the application'
            }
        }
    }
}
