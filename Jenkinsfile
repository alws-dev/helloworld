pipeline {
    agent { docker { image 'gcc:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'gcc -o helloworld helloworld.c'
            }
        }
    }
}