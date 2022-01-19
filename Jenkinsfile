pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'hi ${demo}'
        script{
          echo "${demo}"
        }
      }
    }
      
  }
  environment {
    demo = '1'
  }
}
