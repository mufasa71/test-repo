pipeline {
  agent {
    node {
      label 'agent1'
    }
  }
 
  stages {
    stage('Example') {
      steps {
        nodejs(nodeJSInstallationName: 'node-14.17.6', configId: 'third-party') {
          sh 'npm config ls'
        }
      }
    }
  }
}
