pipeline {
  agent any
     
  stages {
    stage('Checkout'){
      steps{
        echo 'checking out...'
  
      }
    }
    stage('build'){
      steps{
        echo 'building'
    } 
  }
  post{
    success{
      echo 'pipeline completed'
    }
    failure{
      echo 'pipeline failed'
    }
  }
}
