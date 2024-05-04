pipeline {
  agent { label 'any' }
  stages {
    stage('Check version') {
      steps {
        sh "node --version"
        sh "npm --version"
      }
    }
  }
}
