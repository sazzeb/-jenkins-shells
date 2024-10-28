pipeline {
  agent any
  stages {
    stage("verify tooling in place") {
      steps {
        sh '''
          docker version
          docker info
          docker compose version 
          curl --version
          jq --version
        '''
      }
    }
  }
}