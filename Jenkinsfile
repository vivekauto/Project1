pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Initialize'
      }
    }
    stage('Build') {
      steps {
        bat 'java --version'
        bat 'maven --version'
      }
    }
  }
}