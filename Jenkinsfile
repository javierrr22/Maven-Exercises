pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'iniciando compilaci�n'
        sh 'mvn clean install'
        echo 'compilaci�n finalizada'
      }
    }

  }
}