pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'hello world'
          }
        }

        stage('build 2') {
          steps {
            echo 'bye world'
          }
        }

      }
    }

    stage('merge') {
      steps {
        echo 'ho gaya'
      }
    }

  }
}