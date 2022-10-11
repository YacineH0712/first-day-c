pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'apt update -y'
                sh 'apt install build-essential -y'
                sh 'apt-get install manpages-dev -y'
                sh 'gcc -o HelloWorld HelloWorld.c'
            }
        }
    }
}
