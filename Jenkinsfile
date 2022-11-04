pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sleep 2
        echo 'executing build stage'
        sh 'echo "you cab run npm/gradle"'
      }
    }

  }
  environment {
    task = 'demo'
    tag = '0.2.4'
  }
}