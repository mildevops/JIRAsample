pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Sample pipeline'
      }
    }
    stage('Build') {
      steps {
        sh 'ant'
      }
    }
  }
}