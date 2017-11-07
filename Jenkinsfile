pipeline {
  agent any
  stages {
    stage('Laste til DB') {
      steps {
        sh 'whoami'
      }
    }
    stage('Validate DB') {
      parallel {
        stage('Validate DB') {
          steps {
            echo 'OK'
          }
        }
        stage('Sende e-post Are') {
          steps {
            sh 'pwd'
          }
        }
      }
    }
    stage('Verify') {
      steps {
        input(message: 'Skal vi rulle ut?', id: '001', ok: 'JA!!!!!')
      }
    }
  }
}