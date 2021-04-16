pipeline {
    agent { docker { image 'alpine:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'gcc -o helloworld helloworld.c'
            }
        }
    }
}