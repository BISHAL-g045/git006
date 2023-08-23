pipeline {
    agent any

    stages {
        stage('Pre Build') {
            steps {
                sh 'ls -ltr'
                // sh 'git branch "main" "https://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@github.com/BISHAL-g045/git006.git"'
            }
        }
        stage ('Build') {
            steps {
            sh 'pwd'
            sh 'touch a.txt'
            sh 'ls -ltr'
            sh 'whoami'
            sh 'sudo docker ps'
            }
        }
    }
}
