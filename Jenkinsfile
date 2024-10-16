pipeline{
    agent any

    stages{
        stage('test') {
            steps{
                sh 'python3 --version'
            }
        }
        stage('hello') {
            steps{
                sh 'python3 first.py'
            }
        }
    }
}