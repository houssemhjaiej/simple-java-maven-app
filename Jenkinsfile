pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        echo 'Build Demo Application'
      }
    }

    stage('Test') {
      steps {
        echo 'Test Demo Application'
        sh 'sh `mvn  test` '
      }
    }

    stage('Deliver') {
      steps {
        echo 'Deliver  Demo Application'
        sh 'sh `./jenkins/scripts/deliver.sh` '
      }
    }

  }
}