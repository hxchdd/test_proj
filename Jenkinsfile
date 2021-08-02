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
        sh '''mkdir build
cd build
cmake ..
cmake --build .
'''
      }
    }

  }
}