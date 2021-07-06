pipeline {
    agent any{
    tool name: 'MAVEN', type: 'maven'
    }
   
    stages{
        stage('Build'){
            steps{
                 sh 'mvn clean package'
            }
        }
    }
}
        
