pipeline{
    agent any
    stages{
        stage('Cloning'){
            steps{
                git credentialsId: 'github', url: 'https://github.com/kishordhangar/simple-app.git'
            }
        }
        stage('Build'){
            steps{
                sh 'mvn package'
                
            }
               
            }
        }
    }
