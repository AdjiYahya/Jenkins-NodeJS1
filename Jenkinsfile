pipeline {
  agent any

  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/AdjiYahya/Jenkins-NodeJS1'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
         sh '<<Build Command>>'
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
