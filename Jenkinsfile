pipeline {
  agent any
  stages {
    stage('Get Sources') {
      steps {
        parallel(
          "Get Sources": {
            sleep 2
            
          },
          "Get Another Sources": {
            sleep 5
            
          }
        )
      }
    }
    stage('Build') {
      steps {
        sleep 1
      }
    }
  }
}