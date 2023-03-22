pipeline {
  
    agent any
  
    stages {
      stage("build"){
        
          steps{
             echo 'Building application...'
            sh 'ls'
         
          }
      }
      stage("test"){
        
          steps{
             echo 'Testing application...'
            bat 'ls'
          }
      } 
      stage("deploy"){
        
          steps{
            echo 'Deploying application...'
          }
       
      }
    }
    
}
