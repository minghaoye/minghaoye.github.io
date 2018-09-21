pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo '123'
        sleep 12
      }
    }
    stage('default') {
      parallel {
        stage('name') {
          steps {
            echo 'name'
          }
        }
        stage('name') {
          steps {
            echo 'name'
          }
        }
      }
    }
  }
}