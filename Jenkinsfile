pipeline{
    agent any
    environment{
        VAR=1
    }
    stages {
        stage('Test1'){
            steps{
                echo "This is stage 1"
            }
        }
        stage('Test2'){
            steps{
                echo "This is stage 2"
                echo $VAR
            }
        }
         stage('Test3'){
            steps{
                echo "This is stage 3"
            }
        }
