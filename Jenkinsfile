pipeline {
  agent {
    docker {
      image 'centos'
      args 'docker image pull centos:latest'
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