pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git "https://github.com/Pooja-2-5/javarep.git"
      }
    }
     stage('Build') {
       steps{
         publishHTML{[
           allwoMissing:true,
           alwaysLinkTolasBuild:false,
           keepAll:false,
           reportDir:'.',
           reportfiles:'jenhtml.html',
           reportName:'my html publish'
    ]}
       }      
      }
  }
}
     
    
