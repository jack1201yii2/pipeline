pipeline {
    agent any
    stages {
        
        stage ('Build'){
            step{
                pwd
                ls -lrt
                echo "Do something"
            }
        }
        stage('Test'){
            steps{
                touch 1
                echo "Test"
            }
        }
        stage('Deploy'){
            steps {
                echo "Deploy"
            }
        }
    }
}
