pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'iniciando compilación'
      }
    }

    stage('cambio de rama') {
      parallel {
        stage('cambio de rama') {
          steps {
            sh 'git checkout answer4'
          }
        }

        stage('texto') {
          steps {
            echo 'Cambiando de rama'
          }
        }

      }
    }

    stage('compilaci�n') {
      steps {
        sh 'mvn clean install'
        echo 'Chachi'
      }
    }

  }
}