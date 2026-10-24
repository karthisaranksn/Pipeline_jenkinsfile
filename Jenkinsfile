pipeline{
    agent any
    stages{
        stage('git checkout') {
            steps{
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