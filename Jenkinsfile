pipeline {
  agent any
  stages {
    stage('step1') {
      parallel {
        stage('error') {
          steps {
            echo 'eata é a pipeline'
          }
        }

        stage('step 2') {
          steps {
            mail(subject: '[jenkins] Iniciando pipeline', body: 'Estamos iniciando uma pipeline')
          }
        }

      }
    }

  }
}