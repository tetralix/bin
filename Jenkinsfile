pipeline {
  agent any
  stages {
    stage('Get Sources') {
      steps {
        input(message: 'Confirm?', id: 'some ID', ok: 'Yes')
      }
    }
  }
}