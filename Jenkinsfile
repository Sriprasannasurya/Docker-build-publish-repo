pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage('Test') {
      steps {
        echo 'Test - stage'
      }
    }
    stage('Docker Build') {
      steps {
        echo 'Docker build'
      }
    }
  }
}
