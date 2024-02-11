pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'python hello_world.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'copying files to server'
            }
        }
    }
}
