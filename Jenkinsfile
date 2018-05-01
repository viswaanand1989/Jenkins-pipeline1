pipeline {
  agent {
    node {
      label 'TROMSVHV0120'
    }
    
  }
  stages {
    stage('msbuild') {
      steps {
        build 'API-Build'
      }
    }
  }
}