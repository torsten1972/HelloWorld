pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'build'
      }
    }

    stage('Test') {
      steps {
        bat(script: 'dir', returnStatus: true, returnStdout: true, label: 'TestBat', encoding: 'UTF-8')
      }
    }

  }
}