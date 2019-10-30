pipeline {
  agent {
    docker {
      image 'https://hub.docker.com/r/sbiyyala/k8s-demo'
    }

  }
  stages {
    stage('Initialize') {
      steps {
        sh 'echo "Hello world, shishir!"'
      }
    }
  }
  environment {
    UNIQUE_IMAGE_TAG = 'latest'
    UNIQUE_IMAGE_NAME = 'k8sdemo'
    SHOULD_BUILD = 'false'
  }
}