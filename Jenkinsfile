pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'iniciando compilación'
        sh 'mvn clean install'
        echo 'compilación finalizada'
      }
    }

  }
}