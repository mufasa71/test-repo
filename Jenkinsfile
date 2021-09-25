pipeline {
  agent {
    docker {
      image 'alpine/git:v2.30.2'
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
