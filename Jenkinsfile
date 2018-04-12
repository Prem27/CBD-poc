pipeline {
  agent {
    docker {
      image 'docker-apline'
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