pipeline {
    agent any

    stages {
        stage('Pre Build') {
            steps {
                sh 'ls -ltr'
                // sh 'git branch "main" "https://@github.com/BISHAL-g045/git006.git"'
            }
        }
        stage ('Build') {
            steps {
            bat 'pwd'
            bat 'docker ps'
            bat 'dir'
            bat 'whoami'
            }
        }
    }
}
