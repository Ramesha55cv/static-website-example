pipeline {
  agent {
    docker { image 'node:ls ubuntu' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
