pipeline {
  agent any
  stages {
    stage('Setup CI Environment') {
      steps {
        sh 'chmod +x gradlew'
        sh './gradlew setupCIWorkspace'
        sh './gradlew build'
      }
    }
  }
}