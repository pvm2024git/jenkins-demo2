pipeline {
    agent any
    stages {
        stage('Make Folders and files'){
            steps {
                bat '''
                echo "stage 1"
                dir
                '''
            }
        }
        stage ('View') {
            steps {
                bat '''
                dir
                echo "stage 2"
                '''
            }
        }
    }
}