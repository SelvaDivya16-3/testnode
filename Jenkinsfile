pipeline{
  agent any
  stages{
    stage('Install dependencies'){
      steps{
        sh 'npm install'
      }
    }
    stage('test'){
      steps{
        sh 'echo "testing application"'
      }
    }
    stage("deploy nodes application"){
      steps{
        sh 'echo "deploying appli"'
      }
    }
  }
}
