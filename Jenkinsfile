pipeline {
  agent any
  stages {
    stage('Print Tool Version') {
      steps {
        sh 'java -version'
      }
    }

    stage('Build') {
      steps {
        sh ' ./mvnw package'
      }
    }

  }
}