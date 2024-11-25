pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
date'''
      }
    }

    stage('test') {
      steps {
        echo 'test step'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy app'
      }
    }

  }
}