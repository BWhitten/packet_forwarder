pipeline {
  agent {
    docker {
      image 'gcc:4.9'
    }

  }
  stages {
    stage('Build') {
      agent {
        docker {
          image 'gcc:4.9'
        }

      }
      steps {
        sh 'make'
      }
    }

  }
}