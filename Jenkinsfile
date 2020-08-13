pipeline {
  agent {
    docker {
      image 'centos:latest'
      args 'docker pull centos:latest'
    }

  }
  stages {
    stage('Insitialize /Print Message') {
      steps {
        echo 'This is just a test '
      }
    }

  }
}