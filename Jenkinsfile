pipeline {
  agent {
    docker {
      image 'node:6.3'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }
    stage('result') {
      steps {
        sh 'echo "build complate"'
      }
    }
  }
}