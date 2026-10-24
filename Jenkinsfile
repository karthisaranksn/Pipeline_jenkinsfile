pipeline{
    agent any
    stages{
        stage('clean workspace and checkout') {
            steps{
                cleanWs()
                checkout scm
            }
        }
        stage('create directory') {
            steps{
                sh 'mkdir -p new_folder'
                sh 'ls -la'
            }
        }
        
    }
}