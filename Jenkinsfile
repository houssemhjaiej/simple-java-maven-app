pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        echo 'Build Demo Application'
        sh 'sh `mvn  compile` '
      }
    }

  }
}