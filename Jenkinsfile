pipeline {
  agent {
    docker {
      image 'my-jdk11'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "hello world"'
      }
    }

  }
}