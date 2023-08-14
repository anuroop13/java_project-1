pipeline {
 agent any
  
  stages {
    stage('check terraform Version') {
      steps{
       script {
        bat 'terraform --version'
       }
      }
   }
  }
}
