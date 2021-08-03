pipeline {
  agent any
  stages {
    stage('pre') {
      steps {
        echo 'start to build'
      }
    }

    stage('Build') {
      steps {
        bat(script: ' mkdir build cd build cmake .. cmake --build .', returnStatus: true)
      }
    }

  }
}