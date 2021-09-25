pipeline {
  agent {
    node {
      label 'agent1'
    }
  }

  tools { nodejs "node-14.17.6" }
 
  stages {
    stage('Example') {
      steps {
        sh 'npm config ls'
      }
    }
  }
}
