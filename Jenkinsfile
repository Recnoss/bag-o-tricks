pipeline {
  agent any
  stages {
    stage('Sjekk ut kode') {
      steps {
        sh 'whoami'
      }
    }
    stage('Si Hei') {
      steps {
        echo 'Hei Kongsvinger'
      }
    }
    stage('Go? ') {
      steps {
        input(message: 'Er alt OK', id: '001', ok: 'Go go go!')
      }
    }
  }
}