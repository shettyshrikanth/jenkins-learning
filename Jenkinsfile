pipeline {
  agent any
  stages {
    stage('check Docker') {
      steps {
        sh 'docker version'
      }
    }

    stage('Print message') {
      steps {
        echo 'Docker present'
      }
    }

  }
}