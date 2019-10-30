pipeline {
    agent any

    environment {
      UNIQUE_IMAGE_TAG = 'latest'
      UNIQUE_IMAGE_NAME = 'k8sdemo'
      SHOULD_BUILD = 'false'
      IMAGE_NAME = 'sbiyyala/k8s-demo:latest'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
