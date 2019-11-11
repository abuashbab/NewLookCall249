pipeline {
  agent any
  stages {
    stage('My Build') {
      steps {
        echo 'Building..'
        timestamps() {
          echo 'qwqw'
          sleep 2
        }

      }
    }

    stage('My Test') {
      steps {
        echo 'Testing..'
      }
    }

    stage('My Deploy') {
      steps {
        echo 'Deploying....'
      }
    }

  }
}
