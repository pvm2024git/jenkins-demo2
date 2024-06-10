pipeline {
    agent any
    stages {
        stage('Make Folders and files'){
            steps {
                bat '''
                mkdir testingPipeline
                echo "Some Things" > testingPipeline\file.txt
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