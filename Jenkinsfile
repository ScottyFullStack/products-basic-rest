pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'docker build -dit products ./restapi/.'
      }
    }

  }
}