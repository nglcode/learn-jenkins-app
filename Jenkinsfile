pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh '''
                    echo "Test"
                    hostname
                    ls -la
                '''
            }
        }
    }
}
