pipeline {
  agent {
    docker {
      image 'https://docker-repo.vpc.locusdev.net/web/django_service_example:k8s-deploy'
    }

  }
  stages {
    stage('Initialize') {
      steps {
        sh 'echo "Hello world, shishir!"'
      }
    }
  }
}