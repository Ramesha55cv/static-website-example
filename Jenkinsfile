pipeline {
  agent {
    docker { image 'node:new-joker' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
}
