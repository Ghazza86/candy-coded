pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        build 'testing'
      }
    }

    stage('stage1') {
      steps {
        echo 'hello world'
      }
    }

  }
}