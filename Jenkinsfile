pipeline {
    agent any
    tools {
        maven 'MAVEN'
    }
   
    stages{
        stage('Build'){
            steps{
                 sh script: 'mvn clean package'
            }
        }
    }
}
        
