pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        sh 'npm install'
        nodejs('jenk_node') {
          sh 'npm install'
        }

      }
    }

    stage('stage') {
      steps {
        sh 'ng build'
        nodejs 'jenk_node'
      }
    }

  }
}