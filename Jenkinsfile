pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
      stage('clean'){
          steps{
          echo 'mvn clean'
          }
      }
       stage('test'){
          steps{
          echo 'mvn test'
          }
      }
    }
 }
