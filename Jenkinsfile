/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'public.ecr.aws/docker/library/golang:alpine3.19' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
