pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
                sh "python3 pipeline.py"
            }
        }
    }
}