pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh 'gcc -o helloworld helloworld.c'
            }
        }
    }
}