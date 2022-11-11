pipeline {
  agent any
  stages {
    stage('Print Tool Version') {
      steps {
        sh 'mvn --version \\ java --version \\ git --version'
      }
    }

    stage('Build') {
      steps {
        sh ' ./mvnw package'
      }
    }

  }
}