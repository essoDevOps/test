pipeline {
  agent any
  stages {
    stage('k8s') {
      parallel {
        stage('k8s') {
          steps {
            echo 'k8s yaml'
          }
        }

        stage('parallel') {
          steps {
            echo 'thanks'
          }
        }

      }
    }

    stage('esso') {
      steps {
        echo 'God'
      }
    }

    stage('f') {
      steps {
        echo 'hello'
        echo 's'
      }
    }

  }
  environment {
    name = 'value'
  }
}