pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean build -Dlicense.skip=true'
      }
    }

  }
}