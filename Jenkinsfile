pipeline {
    agent any

    stages {
        stage('deploy') {
            steps {
                sh 'docker compose pull'
                sh 'docker compose up -d'
            }
        }
    }
}
