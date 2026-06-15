pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        git "https://github.com/Pooja-2-5/javarep.git"
      }
    }
     stage('Build') {
       steps {
         bat 'javac hello.java'
       }
     }
      stage ('Execute') {
        steps {
          bat 'java hello'
        }
      }
  }
}
     
    
