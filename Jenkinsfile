pipeline {
  agent any
  stages {
    stage('Welcome') {
      parallel {
        stage('Welcome') {
          steps {
            echo 'Hello World'
          }
        }
        stage('') {
          steps {
            echo 'Other Hello World'
          }
        }
      }
    }
  }
}