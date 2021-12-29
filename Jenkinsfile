@Library('roboshop') _

log.info 'Starting'
log.warning 'Nothing to do!'

pipeline {
  agent {
    label 'WORKSTATION'
  }

  triggers {
    pollSCM('*/2 * * * *')
  }

  stages {

    stage('Compile the Code') {
      steps {
        sh 'echo compile code'
      }
    }

    stage('Check the Code Quality') {
      steps {
        sh 'echo Check the code Quality'
      }
    }

    stage('Test Cases') {
      steps {
        sh 'echo Test Cases'
      }
    }

  }

}
