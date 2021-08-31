pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'docker build -dit products ./restapi/.'
      }
    }

  }
}