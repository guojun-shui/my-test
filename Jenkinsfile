pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo '"Build"'
      }
    }
    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }
    stage('Choise') {
      steps {
        input(message: 'Should we continue', ok: 'yes, we should')
      }
    }
    stage('PRD') {
      steps {
        echo 'Begin to deploy prd'
      }
    }
  }
}