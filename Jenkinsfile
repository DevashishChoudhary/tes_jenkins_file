pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
        
         stage('Clean'){
          steps{
          sh 'mvn clean'
          }
      }
      stage('Build'){
          steps{
          sh 'mvn Build'
          }
      }
        stage('Test'){
          steps{
          sh 'mvn test'
          }
      }
        
    }
}
