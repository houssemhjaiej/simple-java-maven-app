pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo ' Build The Demo Application'
        sh 'mvn  compile '
      }
    }

    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }

    stage('Deliver') {
      steps {
        sh './jenkins/scripts/deliver.sh'
      }
    }

  }
}