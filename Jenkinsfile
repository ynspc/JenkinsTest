pipeline {
  agent { label 'ynspc1' }
  stages {
    stage('Check version') {
      steps {
        sh "node --version"
        sh "npm --version"
      }
    }
  }
}
