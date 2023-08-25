pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build coplet'
        timeout(time: 5, unit: 'SECONDS') {
        bat 'ping 127.0.0.1 -n 2 > nul'
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