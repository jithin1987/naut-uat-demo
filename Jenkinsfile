pipeline {
  agent {
    docker {
      image 'node:10'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'echo "hello build"'
      }
    }
  }
}