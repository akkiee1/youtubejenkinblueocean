pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''pwd
              ls



'''
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'test step'
            sleep 15
          }
        }

        stage('test par') {
          steps {
            echo 'test par'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy is done'
      }
    }

  }
}