pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                sh 'your-build-command-here' // e.g., npm install, mvn clean install
            }
        }

        stage('Test') {
            steps {
                sh 'your-test-command-here' // e.g., npm test, mvn test
            }
        }

        stage('Deploy') {
            steps {
                sh 'your-deploy-command-here' // e.g., scp, rsync, docker push
            }
        }
    }
}

