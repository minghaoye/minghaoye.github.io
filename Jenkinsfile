pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            echo '123'
            sleep 12
            echo '123123123'
          }
        }
        stage('error') {
          steps {
            echo '123'
          }
        }
      }
    }
  }
}