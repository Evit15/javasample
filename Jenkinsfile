pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "Build on ${env.BRANCH_NAME}"
      }
    }
    stage('Test') {
      steps {
        echo "Test on ${env.BRANCH_NAME}"
      }
    }
  }
}