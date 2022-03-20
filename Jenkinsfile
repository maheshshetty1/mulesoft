pipeline {
    agent any 
    stages {
        stage('Build'){
            steps{
                git 'https://github.com/maheshshetty1/mulesoft.git'
                bat 'mvn -Dmave.test.failure.ignore=true clean package'
            }
        
        }
    }
}
   
