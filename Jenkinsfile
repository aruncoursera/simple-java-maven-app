pipeline {
  agent any
  stages {
    stage('changecode') {
      steps {
        sh 'echo "Codechange"'
      }
    }
  }
  environment {
    workspace = 'pwd'
  }
}