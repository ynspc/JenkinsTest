pipeline {
  agent { label 'ynspc1' }
  stages {
    stage('Check version') {
      steps {
        sh "node --version"
        // sh "npm --version"
        sh "git status"
        sh "git pull origin master"
      }
    }
  }
}
