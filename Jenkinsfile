pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            echo '123'
            sleep 12
          }
        }
        stage('') {
          steps {
            echo '123'
          }
        }
      }
    }
  }
}