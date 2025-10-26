pipeline {
    agent {
        docker { image 'node:10-alpine' }
    }
    stages {
        stage('Build') {
            steps {
                sh 'node -v'
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}

