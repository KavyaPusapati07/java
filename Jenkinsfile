pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'hi ${demo}'
        sh 'echo("hi ${demo}")'
      }
    }

  }
  environment {
    demo = '1'
  }
}
