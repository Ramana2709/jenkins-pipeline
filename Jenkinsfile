pipeline {
    agent any

    stages {
        stage('Triggered from GitHub') {
            steps {
                sh '''
                echo "Hello from ramana"
                whoami
                pwd
                ls -la
                '''
            }
        }
    }
}
