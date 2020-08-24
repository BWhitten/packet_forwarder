pipeline {
  agent none
  stages {
    stage('Build') {
      agent {
        docker {
          image 'gcc:4.9'
        }

      }
      steps {
        sh 'ls'
      }
    }

  }
}