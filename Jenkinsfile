pipeline {
  agent { docker { image 'python:3.8.2' } }
  stages {
   
    stage('test') {

 

      steps {
        sh 'python main.py'
      }
    }
  }
}


