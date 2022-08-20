pipeline {
  agent any
  stages {
    stage('build-1') {
      parallel {
        stage('build-1') {
          steps {
            echo 'first build'
          }
        }

        stage('build2') {
          steps {
            echo '2nd build'
          }
        }

      }
    }

    stage('compile') {
      parallel {
        stage('compile') {
          steps {
            echo 'first compile'
          }
        }

        stage('2nd compile') {
          steps {
            echo 'print second compile'
          }
        }

      }
    }

  }
}