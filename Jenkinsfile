pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build coplet'
        timeout(time: 5, unit: 'SECONDS') {
        sh 'sleep 10'
}
      }
    }
    stage('Test') {
      steps {
        echo 'Test Complet'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy Complet'
      }
    }
  }
}