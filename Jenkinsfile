pipeline {
  agent {
    node {
      label 'agent1'
    }
  }
 
  tools { nodejs "node" }
 
  stages {
    stage('Example') {
      steps {
        sh 'npm config ls'
      }
    }
  }
}
