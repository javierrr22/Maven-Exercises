pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'iniciando compilaciÃ³n'
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

    stage('compilación') {
      steps {
        sh 'mvn clean install'
        echo 'Chachi'
      }
    }

  }
}