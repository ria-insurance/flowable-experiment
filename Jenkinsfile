pipeline {
  agent any
  stages {
    stage('Print') {
      steps {
        echo 'Hi'
        input(message: 'Enter', id: 'choice', ok: 'A,B')
      }
    }

  }
}