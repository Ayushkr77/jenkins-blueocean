pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            bat 'echo "heloooo"'
          }
        }

        stage('p-build') {
          steps {
            bat 'echo "this is b 2"'
          }
        }

      }
    }

    stage('done') {
      steps {
        bat 'echo "done"'
      }
    }

  }
}