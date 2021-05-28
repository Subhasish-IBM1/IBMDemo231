pipeline {
  agent {
    node {
      label 'task1'
    }

  }
  stages {
    stage('stage1') {
      steps {
        echo 'Hello Stage 1'
      }
    }

  }
  environment {
    prd = 'IBMServer'
  }
}