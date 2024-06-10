pipeline {
    agent any
    stages {
        stage('Make Folders and files'){
            steps {
                bat '''
                mkdir testingPipeline
                '''
            }
        }
        stage ('View') {
            steps {
                bat '''
                dir
                type testingPipeline\text.txt
                '''
            }
        }
    }
}