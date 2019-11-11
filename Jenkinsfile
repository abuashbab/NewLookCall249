pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        timestamps() {
          echo 'qwqw'
          sleep 2
        }

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