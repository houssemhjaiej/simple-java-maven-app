pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo ' Build Demo Application'
        sh 'sh `mvn  compile` '
      }
    }

    stage('Test') {
      steps {
        sh 'sh \'sh `mvn test`\' '
      }
    }

  }
}