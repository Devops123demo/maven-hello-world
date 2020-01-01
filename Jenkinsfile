pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hello World'
          }
        }

        stage('Build2') {
          steps {
            echo 'Hello world 2'
          }
        }

      }
    }

    stage('Final') {
      steps {
        isUnix()
      }
    }

  }
  environment {
    Name = 'Naveen'
  }
}