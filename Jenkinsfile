pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'npm install'
      }
    }

    stage('stage') {
      steps {
        sh 'ng build'
      }
    }

  }
}