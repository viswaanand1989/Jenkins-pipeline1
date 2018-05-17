pipeline {
  agent {
    node {
      label 'Tromsvhv0120'
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
