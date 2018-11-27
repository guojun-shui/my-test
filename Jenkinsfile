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
    stage('') {
      steps {
        input(message: 'Should we continue', ok: 'yes, we should')
      }
    }
  }
}