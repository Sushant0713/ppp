pipeline {
  agent any
  stages {
    stage ( 'Build'){
      
          steps
          { bat 'javac Hello.java'
          }
         }
      stage ('run'){
        
           steps{
             bat 'java Hello'
           }
      }
  }
}
           
