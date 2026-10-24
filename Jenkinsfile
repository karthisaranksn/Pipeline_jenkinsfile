pipeline{
    agent any
    stages{
        stage('clean workspace') {
            steps{
                cleanWs()
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