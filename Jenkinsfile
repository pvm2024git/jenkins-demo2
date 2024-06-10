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
        stage ('Run') {
            steps {
                bat '''
                script.bat
                echo "stage 3"
                '''
            }
        }
    }
}