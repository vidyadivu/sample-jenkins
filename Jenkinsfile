pipeline {
    agent any
    stages {
        stage('first stage'){
            steps{
                echo "this is my first stage"
            }
            stage('second stage'){
            steps{
                echo "this is my second stage"
            }
            stage('build  stage'){
            steps{
                echo "this is my 1st stage in feature branch"
            }
            steps{
                echo "this is my 2nd stage in feature branch"
            }
        }
    }
}