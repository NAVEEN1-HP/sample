pipeline {
  agent any
  stages {
    stage('download') {
      steps {
        nodejs('jenk_node') {
          sh 'npm install'
        }

      }
    }

    stage('stage') {
      steps {
        nodejs('jenk_node') {
          sh 'ng build'
        }

      }
    }

  }
}