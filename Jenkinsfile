pipeline {
 agent any
  
  stages {
    stage('check terraform Version') {
      steps{
       script {
        sh 'terraform --version'
       }
      }
   }
  }
}
