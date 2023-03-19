pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage('CloningRepo'){
            steps{
                echo 'This is satge 1'
                git 'https://github.com/Akarshi2602/DevOpsClassCodes.git'
            }
        }
        stage('Test'){
            steps{
                echo 'This is stage 2'
                sh 'mvn test'
            }
        stage('Package'){
            steps{
                echo 'This is stage 3'
                sh 'mvn package'
            }
        }
        }
    }
}
