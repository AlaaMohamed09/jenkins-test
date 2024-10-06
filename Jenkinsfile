pipeline {
    agent any // 1

    stages {
        stage('Build') { #2
            steps {
                //#3
                echo ' building the application'
            }
        }
        stage('Test') { #4
            steps {
                //#5
                echo ' testing the application'
            }
        }
        stage('Deploy') { #6
            steps {
                //#7
                echo ' deploying the application'
            }
        }
    }
}
