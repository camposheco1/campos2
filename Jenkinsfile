pipeline {
  agent any
  stages {
    stage('phase1') {
      steps {
        sh 'touch hola.txt'
        sleep 10
      }
    }
    stage('phase2') {
      steps {
        echo 'si'
      }
    }
    stage('phase3') {
      steps {
        echo 'si jalo'
      }
    }
  }
}