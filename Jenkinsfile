pipeline {
  agent any
  stages {
    stage('DB Unit') {
      parallel {
        stage('Test') {
          steps {
            echo 'Test Environment'
          }
        }
        stage('DB Unit') {
          steps {
            echo 'DB Unit'
          }
        }
      }
    }
    stage('STG') {
      steps {
        echo 'Environment '
      }
    }
    stage('Preprod') {
      steps {
        echo 'Preprod'
      }
    }
  }
}