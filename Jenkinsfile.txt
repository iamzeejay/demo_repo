pipeline {
    agent any  // Runs on any available agent

    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello World!'
            }
        }
        stage('Stage 2') {
            steps {
                echo 'This is my first Jenkinsfile!'
            }
        }
        stage('Stage 3') {
            steps {
                echo 'Thank you!'
            }
        }
    }
}
