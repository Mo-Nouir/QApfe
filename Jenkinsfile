pipeline {
  
    agent any
  
    stages {
      stage("build"){
        
          steps{
             echo 'Building application...'
            sh 'ls -l'
         
          }
      }
      stage("test"){
        
          steps{
             echo 'Testing application...'
          }
      } 
      stage("deploy"){
        
          steps{
            echo 'Deploying application...'
          }
       
      }
    }
    
}
