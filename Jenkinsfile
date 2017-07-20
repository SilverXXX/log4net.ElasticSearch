pipeline {
  agent any
  stages {
    stage('Start') {
      steps {
        parallel(
          "Start": {
            echo 'test1'
            
          },
          "": {
            echo 'print2'
            
          }
        )
      }
    }
    stage('archive') {
      steps {
        echo 'archive'
      }
    }
  }
}