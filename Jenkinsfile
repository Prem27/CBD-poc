pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'echo "Hello This is Blue-Ocean"'
      }
    }
  }
}