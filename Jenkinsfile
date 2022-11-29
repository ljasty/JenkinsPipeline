pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build'
            }
        }
         stage('Testing:integration & quality') {
            steps {
                echo 'Testing:integration & quality'
            }
        }
        stage('Test:functional') {
            steps {
                echo 'Test:funtional'
            }
        }
         stage('Test:Load &security') {
            steps {
                echo 'Test:Load &security'
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploy'
            }
        }
        stage('release') {
            steps {
                echo 'release'
            }
        }
    }
}
