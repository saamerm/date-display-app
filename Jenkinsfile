pipeline {
    agent none
    stages {
        stage('Front-end') {
            agent {
                docker { image node:carbon-jessie' }
            }
            steps {
                sh 'node --version'
            }
        }
    }
}
