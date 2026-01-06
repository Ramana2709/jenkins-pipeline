pipeline {
    agent any

    stages {
        stage('Triggered from GitHub') {
            steps {
                sh '''
                echo "Hello from Jenkins"
                whoami
                pwd
                ls -la
                '''
            }
        }
    }
}
