pipeline {
    agent any

    stages {

        stage('Create Docker image') {
            steps {
                sh 'docker build -t my-playwright .'
            }
        }
    }
}
