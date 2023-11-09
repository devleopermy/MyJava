pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hi'
          }
        }

        stage('Test') {
          steps {
            bat 'java HelloWorld.java'
          }
        }

      }
    }

  }
}