pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
date
npm i
npm run build'''
      }
    }

    stage('test') {
      steps {
        echo 'test step'
        sh 'npm test'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy app'
        sh 'npm start'
      }
    }

  }
}